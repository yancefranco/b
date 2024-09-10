# Landing Page de nuestra aplicación GreenGrow
flowchart TB
    %% Iniciación del Proyecto
    A1[Identificación del problema de ineficiencia en el almacén] --> A2[Definir alcance del sistema (optimización de rutas, asignación de ubicaciones)]
    A2 --> A3[Identificar normativas y requisitos aplicables (ISO/IEC 12207, operacionales)]
    A3 --> A4[Documento de alcance y lista de requisitos]

    %% Análisis de Requisitos
    B1[Documento de alcance y objetivos] --> B2[Mapeo de necesidades de usuarios (operadores y gerentes)]
    B2 --> B3[Identificación de requisitos funcionales y no funcionales]
    B3 --> B4[Especificaciones detalladas de requisitos]

    %% Diseño del Sistema
    C1[Especificaciones de requisitos] --> C2[Diseño de la arquitectura del sistema]
    C2 --> C3[Definir el modelo de datos y estructura del mapa gráfico]
    C3 --> C4[Diseñar flujos de optimización y asignación automática]
    C4 --> C5[Documento de diseño y diagramas de arquitectura]

    %% Desarrollo e Implementación
    D1[Documento de diseño y especificaciones] --> D2[Desarrollo de funcionalidades clave (automatización, rutas optimizadas)]
    D2 --> D3[Implementación del mapa gráfico]
    D3 --> D4[Pruebas unitarias e integración]
    D4 --> D5[Sistema funcional implementado]

    %% Pruebas y Validación
    E1[Sistema implementado] --> E2[Pruebas de aceptación (usuarios y operarios)]
    E2 --> E3[Validación en condiciones de alta demanda]
    E3 --> E4[Informe de validación y corrección de errores]

    %% Despliegue y Operación
    F1[Sistema validado] --> F2[Despliegue del sistema en producción]
    F2 --> F3[Capacitación de usuarios (operarios y gerentes)]
    F3 --> F4[Operación del sistema y monitorización]
    F4 --> F5[Sistema operativo en producción]

    %% Mantenimiento y Mejora Continua
    G1[Sistema operativo en producción] --> G2[Monitorización y ajustes de rutas]
    G2 --> G3[Gestión de incidencias y mejoras]
    G3 --> G4[Mantenimiento preventivo y correctivo]
    G4 --> G5[Sistema mejorado y actualizado]
