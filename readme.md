1. Instalar la extension mjml para vscode
2. crear un directorio y dentro dos archivos
* index.mjml -> codigo mjml
* index.html -> codigo html compilado de index.mjml
3. en la terminal:
También puede ver un archivo para actualizar automáticamente el archivo de salida (index.html) en cualquier cambio:
```
mjml --watch index.mjml -o index.html
```