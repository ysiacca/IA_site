# Diplomado IA - Módulo 3: Proyecto de Sitio Web

## Estado Actual del Proyecto

Sitio web educativo interactivo para el Diplomado en IA y Ecosistemas Digitales para la Valuación Profesional - Módulo 3: Vibe Coding y Visualización de Datos con Power BI.

---

## Estructura del Sitio

### Páginas Implementadas

1. **Página de Inicio (Temario del Módulo)**
   - Objetivo general del módulo 3
   - Temas del módulo organizados en tarjetas
   - Descripción de 4 semanas de contenido

2. **Sesión 1 (Presentación Interactiva)**
   - Presentación embebida de Google Slides (700px alto × 800px máx ancho)
   - Botón de pantalla completa (icono de expansión)
   - Modal fullscreen para visualización ampliada
   - Enlace a carpeta de recursos en la nube
   - Acordeón desplegable para actividad en clase

3. **Sesión 2 (En Construcción)**
   - Placeholder con mensaje creativo
   - Botones visuales "Próximamente" y "Mantente atento"

### Navegación
- Botón "Inicio" (enlace externo a Campus Virtual)
- Botón "Temario del módulo" (página inicio)
- Botón "Sesión 1" (página tema1)
- Botón "Sesión 2" (página tema2)

---

## Archivos Principales

### `index.html`
- Estructura HTML del sitio
- Presentación embebida de Google Slides
- Modal fullscreen para presentación
- Acordeón interactivo para actividades
- JavaScript para navegación y funcionalidades interactivas

**Funciones JavaScript:**
- `showPage(page)`: Navega entre páginas
- `openSlidesFullscreen()`: Abre presentación a pantalla completa
- `closeSlidesFullscreen()`: Cierra modal fullscreen

### `style.css`
- Variables de color (verde UAEMéx, oro, gris, blanco)
- Estilos responsive
- Animaciones y transiciones
- Estilos para cartas, botones, acordeones

**Variables de Color:**
- `--verde-uaemex`: #004832
- `--oro-uaemex`: #9d8443
- `--gris-oscuro`: #333333
- `--gris-claro`: #f7f9f8
- `--blanco`: #ffffff

### `sesion-2.html` (No usado actualmente)
- Archivo antiguo - puede eliminarse

---

## Detalles Técnicos

### Presentación Google Slides
- **URL**: https://docs.google.com/presentation/d/1-L5H5SPlP9GhZLsylJ6WQ9zX7iI9Bhxl/edit
- **Embed URL**: https://docs.google.com/presentation/d/1-L5H5SPlP9GhZLsylJ6WQ9zX7iI9Bhxl/embed?start=false&loop=false&delayms=3000
- **Dimensiones**: 700px alto (desktop), 550px (móvil)
- **Ancho máximo**: 800px

### Folder de Recursos
- **Placeholder URL**: https://drive.google.com/drive/folders/REEMPLAZA_AQUI
- **Estado**: Requiere actualizar con URL real del folder

### Fuentes y Librerías
- **Font Awesome 6.0.0** (iconos): https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css
- **Google Fonts - Inter**: https://fonts.googleapis.com/css2?family=Inter:opsz,wght@14..32,300;14..32,400;14..32,600;14..32,700;14..32,800

---

## Tareas Pendientes

### Corto Plazo
- [ ] Actualizar URL de folder de recursos en Sesión 1
- [ ] Agregar contenido real a Sesión 2 (o mantener como "En construcción")
- [ ] Probar funcionamiento completo del navegador y presentación en diferentes navegadores

### Mediano Plazo
- [ ] Crear más sesiones (3, 4, 5) con similar estructura
- [ ] Añadir más actividades desplegables en cada sesión
- [ ] Implementar sistema de evaluación/quizzes
- [ ] Agregar videos o recursos adicionales

### Largo Plazo
- [ ] Implementar autenticación de usuarios
- [ ] Agregar sistema de progreso/tracking
- [ ] Base de datos para guardar respuestas de actividades
- [ ] Sistema de certificados

---

## Notas de Desarrollo

### Cambios Realizados
1. Estructura limpia y simplificada (solo encabezado, botones, secciones principales)
2. Estilo unificado con tema verde-oro UAEMéx
3. Presentación Google Slides embebida en Sesión 1
4. Modal fullscreen para mejor visualización de diapositivas
5. Acordeón interactivo para actividades
6. Navegación funcional con data-page attributes

### Convenciones de Código
- IDs generados por GrapesJS (mantener para compatibilidad)
- Classes personalizadas para nuevos elementos
- Naming: kebab-case para clases CSS
- Funciones JavaScript simples y reutilizables

### Responsive Design
- Breakpoint principal: 768px
- Mobile-first approach
- Presentación ajusta altura en dispositivos pequeños

---

## Cómo Continuar

1. **Para agregar nueva sesión:**
   - Copiar estructura de `pagina-tema1`
   - Cambiar ID a `pagina-tema3` (o siguiente número)
   - Agregar botón en navegación con `data-page="tema3"`
   - Actualizar presentación y contenido

2. **Para cambiar presentación de Sesión 1:**
   - Convertir archivo PPTX a Google Slides
   - Obtener nueva URL
   - Reemplazar en `embed src=` en HTML

3. **Para actualizar folder de recursos:**
   - Crear carpeta en Google Drive
   - Copiar URL
   - Reemplazar `https://drive.google.com/drive/folders/REEMPLAZA_AQUI`

4. **Para modificar estilos:**
   - Editar variables de color en `:root` en `style.css`
   - Mantener responsive design
   - Probar en móvil

---

## Contacto / Soporte

- Proyecto: Diplomado IA Valuación - UAEMéx FECOVAL
- Módulo: 3 - Vibe Coding y Visualización de Datos
- Ruta: `/OneDrive - Universidad Autónoma del Estado de México/DECyD/Proyectos/Diplomado IA/Sitio`

---

**Última actualización**: 04 de junio de 2026
**Estado**: En desarrollo activo
