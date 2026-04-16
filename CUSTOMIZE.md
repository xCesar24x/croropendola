# 🎨 Guía de Customización

## Cambiar la Velocidad del Carrusel

En `index.html`, busca esta línea:

```javascript
setInterval(updateCarousel, 5000);
```

- `5000` = 5 segundos
- Cambia a `3000` para 3 segundos (más rápido)
- Cambia a `8000` para 8 segundos (más lento)

## Cambiar Colores de la Marca

Busca las variables CSS y modifica los valores:

```css
:root {
    --madera-oscura: #482318;    /* Color principal (marrón) */
    --madera-clara: #bc8a5f;     /* Color secundario (tan) */
    --oro: #eec12d;              /* Color de énfasis (dorado) */
    --fondo: #fcfaf7;            /* Color de fondo */
}
```

### Generador de Paletas
- https://coolors.co/
- https://www.color-hex.com/

## Cambiar Fuentes

Las fuentes se importan de Google Fonts:

```html
<link href="https://fonts.googleapis.com/css2?family=Uncial+Antiqua&family=Libre+Baskerville:ital,wght@0,400;0,700;1,400&family=Montserrat:wght@600&display=swap" rel="stylesheet">
```

Para cambiar:
1. Ve a https://fonts.google.com/
2. Selecciona nuevas fuentes
3. Copia el link proporcionado
4. Reemplaza el link en el HTML
5. Actualiza el CSS para usar los nuevos nombres

## Agregar Nuevas Casitas al Carrusel

Para agregar una nueva artesanía:

### 1. En el HTML, agrega una nueva slide:

```html
<div class="slide"><img src="assets/images/NuevaCasa.jpeg"></div>
```

### 2. Agrega el texto de historia correspondiente:

```html
<div class="history-text">
    <h3>Nombre del Estilo</h3>
    <p>Descripción breve de la artesanía.</p>
</div>
```

El carrusel se actualizará automáticamente.

## Cambiar Textos

### Título Principal
```html
<h1>Oropéndola</h1>
```

### Subtítulo
```html
<div class="subtitle">Artesanías en Madera</div>
```

### Descripción del Equipo
```html
<div class="artisans-description">
    "Tu texto aquí..."
</div>
```

### Nombre de la Colección
```html
<div class="collection-header">Colección "Nombre"</div>
```

## Cambiar Enlaces de Contacto

### WhatsApp
```html
<a href="https://wa.me/50683336102" class="btn btn-highlight" target="_blank">
    <!-- Cambia el número: 50683336102 -->
</a>
```

### Instagram
```html
<a href="https://www.instagram.com/croropendola/" class="btn" target="_blank">
    <!-- Cambia: croropendola -->
</a>
```

### Facebook
```html
<a href="https://www.facebook.com/share/1BePMb6QJY/" class="btn" target="_blank">
    <!-- Cambia la URL del perfil -->
</a>
```

### Email
```html
<a href="mailto:oropendolartesanias@gmail.com" class="btn" target="_blank">
    <!-- Cambia el email -->
</a>
```

## Información de Contacto

Busca esta sección:

```html
<div class="info-item"><i class="fas fa-map-marker-alt"></i> Ulloa, Heredia, Costa Rica</div>
<div class="info-item"><i class="fas fa-phone-alt"></i> (+506) 8333 6102</div>
<div class="info-item"><i class="fas fa-truck"></i> Envíos por Correos de CR | Retiro en tienda</div>
```

Cambia según tus datos.

## Cambiar Tamaño del Logo

Busca:

```css
.logo-container {
    width: 140px;      /* Cambia aquí */
    height: 140px;     /* Y aquí */
    ...
}
```

## Cambiar Estilos del Botón

Busca:

```css
.btn {
    padding: 15px 20px;        /* Tamaño */
    border-radius: 12px;       /* Redondez */
    font-size: 0.9rem;         /* Tamaño de fuente */
    ...
}
```

## Agregar Sombras o Efectos

### Más sombreado:
```css
box-shadow: 0 10px 30px rgba(72, 35, 24, 0.3); /* Aumenta el 0.3 */
```

### Efecto hover personalizado:
```css
.btn:hover {
    box-shadow: 0 15px 40px rgba(72, 35, 24, 0.2);
    transform: translateY(-3px);
}
```

## Recursos Útiles

- **Inspeccionar Elementos**: F12 en el navegador
- **Gradientes CSS**: https://cssgradient.io/
- **Sombras CSS**: https://www.cssmatic.com/box-shadow
- **Animaciones**: https://animate.style/
- **Íconos**: https://fontawesome.com/icons

---

¡Diviértete personalizando tu sitio! 🎨✨
