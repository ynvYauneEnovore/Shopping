# Carrito de Compra con Ajax, Laravel y jQuery

![Logo de la aplicación](logo.png)

Esta aplicación es un carrito de compra implementado utilizando la combinación de Ajax, Laravel y jQuery. Proporciona una interfaz fácil de usar para que los usuarios puedan seleccionar y comprar productos de una tienda en línea.

## Características principales

- **Agregado y eliminación de productos**: Los usuarios pueden agregar productos al carrito de compra y eliminarlos cuando sea necesario.
- **Actualización en tiempo real**: La aplicación utiliza Ajax para actualizar el carrito de compra en tiempo real sin necesidad de recargar la página.
- **Funcionalidad de búsqueda**: Los usuarios pueden buscar productos por nombre o categoría para encontrar rápidamente lo que desean comprar.
- **Proceso de pago**: El carrito de compra permite a los usuarios completar el proceso de pago de manera segura y eficiente.
- **Autenticación de usuarios**: Los usuarios pueden registrarse, iniciar sesión y gestionar su cuenta para realizar un seguimiento de sus pedidos y detalles de pago.
- **Administración de productos**: Los administradores pueden agregar, editar y eliminar productos desde el panel de administración de la aplicación.

## Tecnologías utilizadas

- **Laravel**: Un framework de desarrollo de aplicaciones web rápido y eficiente en PHP.
- **jQuery**: Una biblioteca de JavaScript rápida y concisa que simplifica la manipulación del DOM y la interacción con el servidor.
- **Ajax**: Una técnica de desarrollo web que permite realizar solicitudes asíncronas al servidor sin recargar la página completa.

## Requisitos de instalación

Asegúrate de tener los siguientes requisitos antes de instalar y ejecutar la aplicación:

- PHP >= 7.4
- Composer
- Node.js
- Laravel >= 8

## Instalación

1. Clona el repositorio en tu máquina local:

`git clone https://github.com/ynvYauneEnovore/Shopping.git`

2. Navega hasta el directorio del proyecto:

`cd Shopping`


3. Instala las dependencias de PHP utilizando Composer:

`composer install`


4. Instala las dependencias de JavaScript utilizando npm:

`npm install`


5. Copia el archivo de configuración `.env.example` y renómbralo a `.env`. Luego, actualiza las variables de entorno según tu configuración.

6. Genera una clave de aplicación única:

`php artisan key:generate`


7. Ejecuta las migraciones de la base de datos:

`php artisan migrate`


8. Inicia el servidor de desarrollo:

`php artisan serve`


9. Accede a la aplicación en tu navegador web en `http://localhost:8000`.

## Contribución

Si deseas contribuir a este proyecto, sigue los siguientes pasos:

1. Haz un fork del repositorio.
2. Crea una rama de características (`git checkout -b feature/nueva-caracteristica`).
3. Realiza los cambios y haz commits de tus modificaciones (`git commit -am 'Agrega una nueva característica'`).
4. Haz push a la rama (`git push origin feature/nueva-caracteristica`).
5. Abre una solicitud de extracción en GitHub.

## Licencia

Este proyecto está bajo la Licencia [MIT](LICENSE).

---

¡Disfruta usando nuestro carrito de compra con Ajax, Laravel y jQuery! Si tienes alguna pregunta o sugerencia, no dudes en contactarnos.

**Autores:**
- Yovan Enovore ([@ynvYauneEnovore](https://github.com/ynvYauneEnovore))




<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework.

You may also try the [Laravel Bootcamp](https://bootcamp.laravel.com), where you will be guided through building a modern Laravel application from scratch.

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains over 2000 video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.

## Laravel Sponsors

We would like to extend our thanks to the following sponsors for funding Laravel development. If you are interested in becoming a sponsor, please visit the Laravel [Patreon page](https://patreon.com/taylorotwell).

### Premium Partners

- **[Vehikl](https://vehikl.com/)**
- **[Tighten Co.](https://tighten.co)**
- **[Kirschbaum Development Group](https://kirschbaumdevelopment.com)**
- **[64 Robots](https://64robots.com)**
- **[Cubet Techno Labs](https://cubettech.com)**
- **[Cyber-Duck](https://cyber-duck.co.uk)**
- **[Many](https://www.many.co.uk)**
- **[Webdock, Fast VPS Hosting](https://www.webdock.io/en)**
- **[DevSquad](https://devsquad.com)**
- **[Curotec](https://www.curotec.com/services/technologies/laravel/)**
- **[OP.GG](https://op.gg)**
- **[WebReinvent](https://webreinvent.com/?utm_source=laravel&utm_medium=github&utm_campaign=patreon-sponsors)**
- **[Lendio](https://lendio.com)**

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
