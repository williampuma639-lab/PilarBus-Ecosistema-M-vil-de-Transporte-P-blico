# PilarBus
Aplicación móvil y plataforma web para consultar recorridos de colectivos en tiempo real en Pilar.
## 1. Justificación metodológica
Para desarrollar el proyecto PilarBus se selecciona la metodología ágil Scrum, debido a que se trata de un proyecto con requisitos cambiantes y un alto nivel de incertidumbre.

La aplicación deberá permitir a los ciudadanos consultar recorridos de colectivos en tiempo real. Sin embargo, durante su desarrollo pueden surgir nuevas necesidades a partir de las opiniones de los usuarios.

Scrum permite organizar el trabajo en períodos cortos llamados Sprints, que generalmente duran entre dos y cuatro semanas.

Al finalizar cada Sprint, el equipo presenta una versión funcional del producto, recibe comentarios y realiza las mejoras necesarias.

Ventajas de utilizar Scrum:
- Permite adaptarse rápidamente a los cambios.
- Facilita la comunicación entre los integrantes.
- Permite detectar errores durante el desarrollo.
- Entrega resultados funcionales en períodos cortos.
- Incorpora las opiniones de los usuarios.
- Mejora la organización y distribución de tareas.
¿Por qué no utilizar Cascada?

El modelo Cascada requiere definir y aprobar prácticamente todos los requisitos antes de comenzar el desarrollo. Esto sería una desventaja para PilarBus porque sus funcionalidades pueden cambiar semanalmente.

Por lo tanto, Scrum es más adecuado porque permite desarrollar, probar y mejorar la aplicación continuamente.

## 2. Organización del trabajo

Para este parcial, la planificación se realiza de manera individual. Se simula un equipo de desarrollo que utiliza Scrum para organizar las tareas del proyecto.

Se definen los siguientes roles:
- Product Owner: representa las necesidades de los usuarios.
- Scrum Master: organiza el proceso y controla que se cumpla la metodología.
- Equipo de desarrollo: realiza las tareas necesarias para construir la aplicación.

## 3. Control de versiones y Pull Requests

GitHub permite guardar las distintas versiones del proyecto y organizar los cambios.

El procedimiento de trabajo sería:
1. Crear una rama (Branch) para cada modificación.
2. Realizar los cambios correspondientes.
3. Crear un Pull Request (PR) para proponer la incorporación de esos cambios.
4. Revisar los cambios y comprobar que no existan errores.
5. Integrar los cambios a la rama principal (main).

## 4. Integración y entrega continua (CI/CD)

Se propone utilizar GitHub Actions para automatizar las verificaciones del proyecto.

El proceso se divide en tres etapas:

- Build (Construcción): prepara el proyecto para su ejecución.
- Test (Pruebas): verifica que las funcionalidades trabajen correctamente.
- Deploy (Despliegue): publica la versión aprobada de la aplicación.

Estas etapas permitirían detectar errores y facilitar la entrega de nuevas versiones.

