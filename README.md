# First Project Node.js

Este es un proyecto básico desarrollado con Node.js. Fue creado como parte de un aprendizaje práctico para implementar un servidor web y desplegarlo en Render.

## 🚀 Despliegue en vivo

Puedes acceder al proyecto en: [https://first-project-nodejs.onrender.com/](https://first-project-nodejs.onrender.com/)

## 🛠️ Tecnologías utilizadas

- **Node.js**: Para crear el servidor.
- **Render**: Para el despliegue.
- **JavaScript**: Lenguaje principal.

## ⚙️ Instalación y uso
Sigue estos pasos para ejecutar el proyecto localmente:

1. Clona el repositorio:
   ```bash
   git clone https://github.com/yeider04/first-project-nodejs.git
   cd first-project-nodejs

2. Instala las dependencias:
    ```bash
    npm install

3. Inicia el servidor:
    ```bash
    npm start

4. Abre tu navegador en http://localhost:3000 para ver el servidor funcionando.

## 📚 Descripción de las rutas

| Ruta          | Método | Descripción                     |
|---------------|--------|---------------------------------|
| `/`           | GET    | Página principal del servidor. |
| `/about`      | GET    | Página de información.         |
| `/contact`    | POST   | Enviar información de contacto.|

## 📝 Notas
El servidor está configurado para escuchar en el puerto 3000 localmente.
Puedes personalizar las rutas en el archivo routes.
