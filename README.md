# WTech Store

Tienda en línea de accesorios para celulares con carrito, pagos con PayPal, panel de administración y un diseño oscuro estilo cyberpunk.

**Sitio en vivo:** [store.w-tech.uk](https://store.w-tech.uk)

## Qué incluye

- Catálogo con filtros, ofertas y detalle de producto.
- Carrito, checkout con autocompletado de dirección y pagos con PayPal.
- Registro e inicio de sesión (Supabase Auth, incluido Google).
- Panel de administración: dashboard, productos (crear, editar, subir imágenes) y pedidos.
- Formulario de contacto que envía correo por SMTP.

## Stack

| Capa | Tecnología |
|---|---|
| Frontend | React 19, Vite, Tailwind CSS (`client/`) |
| Backend | Node.js, Express (`server/`) |
| Base de datos y auth | Supabase (PostgreSQL) |
| Pagos | PayPal |
| Hosting | Cloudflare Pages (frontend) y Fly.io (API) |

## Desarrollo local

```bash
# Frontend
cd client
cp .env.example .env   # completa con tus claves
npm install
npm run dev

# Backend
cd server
cp .env.example .env
npm install
npm run dev            # http://localhost:3001
```

La documentación técnica completa (esquema de base de datos, rutas, despliegue) está en [`PROJECT.md`](PROJECT.md).

## Autor

Hecho por [Williams Villavizar](https://wilrd14.dev), desarrollador web en Santo Domingo, República Dominicana. [Ver portafolio](https://wilrd14.dev).
