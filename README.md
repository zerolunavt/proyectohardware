# Consola de Juegos Retro Portátil — Carpeta de Campo

Proyecto del **Laboratorio de Hardware** — E.E.S.T. N° 2 "René Favaloro" — 4° 1°.
Profesor: Cáceres Alejandro.

Integrantes: Eleonora Sacchi, Bianca Volggi, Palomeque Melanie, Lorenzo Coronel.

Consola portátil con Arduino Nano, pantalla TFT ILI9341 (SPI), buzzer pasivo y 5 pulsadores (`INPUT_PULLUP`), con los juegos Pong, Tetris y Snake programados en C++.

## Contenido del repositorio

| Ruta | Descripción |
|---|---|
| `index.html` | Carpeta de campo en formato web (con índice lateral) |
| `assets/` | Logo e imágenes de los componentes |
| `docs/Carpeta_de_Campo_Consola_Retro_Portatil.docx` | Versión en Word, lista para imprimir |
| `.nojekyll` | Evita que GitHub Pages procese el sitio con Jekyll |

## Cómo publicarlo en GitHub Pages

1. Crear un repositorio nuevo en GitHub (por ejemplo `consola-retro-portatil`).
2. Subir **todo el contenido de esta carpeta** a la raíz del repositorio (`index.html`, `assets/`, `docs/`, `.nojekyll`, `README.md`).
3. Ir a **Settings → Pages**.
4. En **Build and deployment**, elegir **Deploy from a branch**, rama `main` y carpeta `/ (root)`. Guardar.
5. Después de uno o dos minutos el sitio queda disponible en:
   `https://<tu-usuario>.github.io/<nombre-del-repositorio>/`

Con la línea de comandos:

```bash
git init
git add .
git commit -m "Carpeta de campo: Consola de Juegos Retro Portátil"
git branch -M main
git remote add origin https://github.com/<tu-usuario>/<nombre-del-repositorio>.git
git push -u origin main
```

## Probarlo en local

Abrir `index.html` en el navegador, o desde esta carpeta ejecutar `python3 -m http.server` y entrar a `http://localhost:8000`.
