# Introducción a Angular

Introducción a Angular version 14.2.2.

## Secciones vistas

1. [Generar un proyecto en Angular](##2).
2. [Explicación de cada archivo del proyecto](##3).
3. [¿Qué es un App Component?](##4)
4. Generación de un Component llamado "Contador".
5. Métodos del Component "Contador".

## Generar un proyecto en Angular

Se puede descargar este proyecto directamente desde este repositorio o ejecutar la siguiente sentencia en consola dentro de la carpeta a utilizar para el proyecto `ng new 01-bases`

## Explicación de cada archivo del proyecto.

Archivo `tsconfig.json`: Archivo de configuración de TypeScript.

Archivo `tsconfig.spec.json`: Archivo de configuración de TypeScript, extendido de `tsconfig.json`.

Archivo `tsconfig.app.json`: Archivo de configuración de TypeScript, extendido de `tsconfig.json`.

Archivo `README.md`: Archivo de texto, con códigos, títulos, para dar descripciones del proyecto.

Archivo `package.json`: Archivo delicado, se recomienda no hacer modificaciones manuales. Archivo para agregar dependencias se puede utilizar comandos que se verán más adelante.

Archivo `package-lock.json`: Archivo que explica como se construyó el proyecto y sus módulos.

Archivo `karma.conf.js`: Archivo que configuración para las pruebas unitarias y de integración del proyecto.

Archivo `angular.json`: Archivo que contiene configuraciones del proyecto, como favicon, assets, styles entre otros.

Archivo `.gitignore`: Archivo que indica los archivos que no se quiere subir mediante Git.

Directorio `node_modules/`: Paquetes instalados para Angular y su desarrollo.

Directorio `src/`: Dentro de esta carpeta se encuentra lo siguiente:

* `app/`: Contiene los archivos para la raiz del proyecto.
* `assets/`: Contiene los archivos y recursos estáticos, por ejemplo: imágenes, sonidos, etc.
* `environments/`: Contiene los archivos para indicarle a Angular las variables de entorno, ya sea de desarrollo y producción.

| Archivo            | Descripción                                                              |
|--------------------|--------------------------------------------------------------------------|
| app.component.css  | Archivo que hace relación al estilo que se aplicará al componente "app". |
| app.component.html | Archivo que contiene el código HTML del componente "app".                |
| app.component.ts   | Archivo que contiene la clase de Typescript del componente "app".        |
| app.module.ts      | Archivo que contiene la clase de Typescript del módulo "app".            |

## ¿Qué es un App Component?

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
