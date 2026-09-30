# Portafolio / CV — Zeferino Velasco Martínez

Portafolio personal en formato de CV, construido con **Bootstrap**, para mostrar mi perfil, habilidades y proyectos como estudiante de Ingeniería en Sistemas Computacionales.

---

## 📄 Descripción del proyecto

- **Link de descarga de la plantilla:** https://startbootstrap.com/theme/freelancer

### Menús / secciones del portafolio

| Sección | Descripción |
|---|---|
| **Inicio (encabezado)** | Foto de perfil, nombre completo, título profesional y datos de contacto rápidos (correo, teléfono, ubicación) y enlaces a redes sociales. |
| **Sobre mí** | Breve presentación personal: quién soy, qué estudio y mi experiencia general en desarrollo de software. |
| **Habilidades** | Barras de progreso con mis conocimientos actuales (Java, Android Studio, HTML/CSS/JS, bases de datos) y una habilidad que quiero aprender (React). |
| **Experiencia / Educación** | Tarjetas con mi trayectoria académica y prácticas o cursos relevantes. |
| **Proyectos** | Galería de 3 proyectos con imagen, y al hacer clic se abre un modal con el nombre y la descripción de cada uno. |
| **Contacto** | Formulario de contacto (nombre, correo, mensaje). |
| **Footer** | Ubicación, enlaces a redes sociales y una nota sobre el sitio. |

---

## 🛠️ Proceso de creación

1. **Elección y descarga de la plantilla.** Elegí la plantilla *Freelancer* de Start Bootstrap porque ya venía con una estructura de una sola página (one-page) con navegación, sección de portafolio con modales, y formulario de contacto — ideal como punto de partida para un CV.

2. **Renombrado de archivos.** Según lo pedido en la actividad, renombré `css/styles.css` a `css/portafolio.css` y `js/scripts.js` a `js/portafolio.js`, actualizando las referencias `<link>` y `<script>` en el `index.html`.

3. **Transformación de "portafolio de diseñador" a "CV".** La plantilla original estaba pensada para un freelancer creativo (Portfolio / About / Contact). La modifiqué para que se viera como un currículum:
   - Agregué un encabezado con foto de perfil, nombre, título y datos de contacto directos (correo, teléfono, ubicación), típico de un CV.
   - Agregué una sección nueva de **Habilidades** con barras de progreso, que la plantilla original no tenía.
   - Agregué una sección nueva de **Experiencia / Educación** con tarjetas tipo línea de tiempo.
   - Reduje la sección de Portfolio de 6 a 3 proyectos, y reemplacé las imágenes y textos de ejemplo (Lorem ipsum) por mis propios proyectos reales.
   - Cambié el menú de navegación para reflejar las nuevas secciones (Sobre mí, Habilidades, Experiencia/Educación, Proyectos, Contacto).

4. **Contenido personal.** Reemplacé todos los textos de ejemplo de la plantilla por mi información real: mi foto, mi nombre, mi descripción personal, mis habilidades y mis tres proyectos (Detección de lenguas de señas, RutaGo y Hospital El Niño Doctor), cada uno con su propia descripción dentro del modal correspondiente.

5. **Personalización visual (paleta de colores).** La plantilla original usa un turquesa/verde azulado como color principal. Para que se viera más profesional y menos genérico, cambié la paleta a **navy profundo + dorado**:
   - Encabezado, sección de Habilidades, menú de navegación y footer ahora usan tonos navy en vez del turquesa original.
   - Botones, las estrellas de los divisores y el overlay al pasar el mouse sobre un proyecto ahora usan un dorado como color de acento.
   - Esto se hizo agregando un bloque de reglas CSS al final de `css/portafolio.css`, sobrescribiendo las variables de color de Bootstrap sin tener que reescribir todo el archivo compilado.

6. **Ajustes de foto y de imágenes de proyectos.**
   - La foto de perfil ahora se recorta en forma circular y pareja (`object-fit: cover` + `border-radius: 50%`), en vez de mostrarse como un rectángulo suelto.
   - Las 3 imágenes de la sección Proyectos ahora se recortan automáticamente a la misma proporción (4:3), para que se vean del mismo tamaño en la cuadrícula aunque las capturas originales tuvieran formas distintas (una del editor de código, una de un celular en vertical, una de una app).

---

## 🖼️ Capturas de pantalla


```markdown
![Encabezado / Inicio](assets/img/inicio.png)
![Sección Sobre mí y Habilidades](assets/img/habilidades.png)
![Sección Experiencia y Educación](assets/img/experiencia.png)
![Sección Proyectos](assets/img/proyecto.png)
```


## 👤 Autor

**Zeferino Velasco Martínez** — Instituto Tecnológico de Oaxaca