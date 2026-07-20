# Willitek Web Source

This is the source code for the Willitek website. It is built using standard HTML, CSS, and JavaScript.

## Development

To view the website locally during development, you can open `src/index.html` directly in your web browser, or use a local development server like VS Code's "Live Server" extension for a better experience.

## Deployment

This project is configured to automatically deploy to GitHub Pages whenever changes are pushed to the `main` branch. 

Deployment is handled via the GitHub Actions workflow located in `.github/workflows/deploy.yml`, which directly hosts the contents of the `src/` directory.
