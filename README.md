# Práctica 7 - Web App con Dockerfile y Docker Compose

Aplicación web en Python + Flask que se conecta a una base de datos MySQL, orquestada con Docker Compose.

## Estructura

- `src/app.py`: Código fuente de la aplicación
- `src/Dockerfile`: Imagen personalizada de Python + Flask
- `docker-compose.yml`: Define los servicios `app` y `db`

## Cómo ejecutar

```bash
docker compose up -d
