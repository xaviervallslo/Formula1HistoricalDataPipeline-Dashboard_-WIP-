# 🏎️ Formula 1 Historical Data Pipeline & Dashboard (WIP)

> 🚧 **Work In Progress**
>
> Este proyecto aún se encuentra en desarrollo y seguirá incorporando nuevas funcionalidades y visualizaciones.

## 📖 Descripción

Este proyecto automatiza la recopilación y procesamiento de datos históricos de Fórmula 1 utilizando Python.

El objetivo es construir un pipeline de datos que permita obtener información actualizada de:

- Grandes Premios
- Pilotos
- Equipos

Posteriormente, los datos son transformados y utilizados como fuente para un dashboard desarrollado en Power BI.

---

## ⚙️ Tecnologías

- Python
- Pandas
- NumPy
- Requests
- Matplotlib
- Power BI
- Excel

---

## 📂 Estructura del proyecto

```
.
├── F1.py              # Script principal
├── F1.ipynb           # Notebook de desarrollo
├── F1.xlsx            # Dataset generado
├── Formula1.pbix      # Dashboard Power BI
├── F1.bat             # Ejecución automática
└── README.md
```

---

## 🚀 Funcionalidades actuales

- Extracción automática de datos históricos desde Formula1.com.
- Limpieza de nombres de Grandes Premios.
- Limpieza y normalización de pilotos.
- Generación de tablas de:
  - Carreras
  - Pilotos
  - Equipos
- Exportación a Excel.
- Dashboard en Power BI.

---

## 🔄 Próximas mejoras

- [ ] Automatizar completamente el proceso ETL.
- [ ] Añadir estadísticas por piloto.
- [ ] Añadir estadísticas por equipo.
- [ ] Comparativas entre temporadas.
- [ ] Incorporar más métricas de rendimiento.
- [ ] Optimizar el código.

---

## 📊 Objetivo

Crear un sistema automatizado para analizar la historia de la Fórmula 1 mediante procesos ETL y visualización de datos.

---

## ⚠️ Estado

Proyecto en desarrollo (**WIP**).

Las funcionalidades pueden cambiar y el código seguirá mejorando.
