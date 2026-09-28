# DocuMind AI (Nombre en código)
**Transformando contenido crudo en experiencias de aprendizaje inteligentes.**

## 📖 Visión del Proyecto
DocuMind es una plataforma B2B (SaaS) diseñada para instituciones educativas privadas, academias, bootcamps y creadores de contenido. Nuestra herramienta toma materiales de estudio desorganizados o en bruto y, mediante inteligencia artificial, los transforma instantáneamente en documentos PDF altamente didácticos, estructurados y enriquecidos con asistentes de estudio integrados.

No somos un simple conversor de texto a PDF; somos un motor de optimización pedagógica.

## 🎯 Público Objetivo (B2B)
*   **Institutos Terciarios y Universidades Privadas:** Que buscan modernizar sus apuntes y estandarizar la calidad de su material bibliográfico.
*   **Academias de Programación e Idiomas:** Que necesitan iterar y actualizar sus contenidos rápidamente sin depender de un equipo de diseño editorial completo.
*   **Creadores de Cursos Independientes:** Que desean ofrecer material descargable de calidad premium (valor agregado) a sus alumnos con cero esfuerzo manual.

## ✨ Características Principales

### 1. Estructuración Pedagógica Automática
El motor de IA ingiere texto plano, desgrabaciones de clases o apuntes caóticos y devuelve un documento con jerarquía visual: títulos claros, viñetas, resaltado de conceptos clave y bloques de atención.

### 2. Tutoría y Enriquecimiento Integrado (Study AI)
La plataforma no solo formatea, sino que expande el conocimiento:
*   **Investigación Complementaria:** Agrega recuadros de "Para saber más" con información de contexto que el profesor no incluyó originalmente.
*   **Glosarios Dinámicos:** Extracción y definición automática de jerga técnica.
*   **Analogías Didácticas:** Traducción de conceptos de alta complejidad a ejemplos cotidianos.

### 3. Exportación Profesional
Generación de documentos PDF con diseño editorial limpio, optimizados tanto para lectura en pantallas (tablets/monitores) como para impresión en papel (A4).

## 💼 Modelo de Negocio Propuesto
El enfoque está puesto en la venta corporativa (B2B) con ingresos recurrentes:
1.  **Tier Inicial (Creadores):** Suscripción mensual con un límite de conversiones y páginas generadas al mes, con marca de agua discreta de la plataforma.
2.  **Tier Profesional (Academias):** Mayor volumen de conversiones, PDFs en marca blanca (con el logo y los colores institucionales del cliente).
3.  **Tier Institucional:** Integración vía API directamente en las plataformas (LMS) de las instituciones, facturación por uso de servidor y volumen de alumnos.

## 🛠 Stack Tecnológico Inicial (MVP)
*   **Backend:** Node.js + Express (Servidor rápido, asíncrono y escalable).
*   **Inteligencia Artificial:** Gemini API (Procesamiento de lenguaje natural, estructuración de contenido e investigación de contexto).
*   **Generación de Documentos:** Librería de renderizado (Puppeteer / PDF-lib) para inyectar los resultados de la IA en plantillas HTML/CSS predefinidas y exportarlas a PDF.
*   **Frontend (Dashboard Cliente):** Interfaz web simple con HTML, CSS (Tailwind) y Vanilla JavaScript para la carga de documentos y selección de estilos.

## 🚀 Hoja de Ruta (Roadmap)
- [x] Definición del alcance y pivotaje a modelo B2B.
- [ ] Fase 1: Setup del servidor Express y creación del endpoint de recepción de texto.
- [ ] Fase 2: Integración de la API de Gemini (Prompt Engineering para estructuración y Study AI).
- [ ] Fase 3: Diseño de la plantilla CSS maestra y generación del primer archivo PDF de prueba.
- [ ] Fase 4: Desarrollo de la interfaz de usuario (Dashboard) para pegar el texto y descargar el resultado.
- [ ] Fase 5: Implementación del sistema de control de uso (Rate Limiting por cliente).
