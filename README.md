# Track 03 · EdTech: Aprender de verdad

**Talavera Valley Hackathon 2026 · 12 al 14 de noviembre · Tec de Monterrey, Campus Puebla**

> Construyan una empresa que lleve a un joven de elegir carrera a su primer ingreso digno, con datos reales y habilidades demostradas, no solo con un título.

Sofía (17) se inscribe en Derecho. Mateo (18) quiere construir ya. Su producto es para uno de ellos, o para los dos.

## Lo que encuentran aquí

| Carpeta | Qué hay | Para qué |
|---|---|---|
| [`reto/`](reto/) | `Reto_EdTech.html` (ábranlo en el navegador) y `Reto_EdTech_Deck.pdf` | Las reglas, la rúbrica y los premios |
| [`repositorio/`](repositorio/) | `Repositorio_EdTech_completo.csv` y `Repositorio_EdTech.pdf` | Datos públicos de México en seis bloques (carreras, trayectoria, primer empleo, emprender, costo y futuro), cada uno con su fuente y su enlace |
| [`panel/`](panel/) | `Panel_EdTech.html` | El planteamiento del panel del jueves |
| [`equipos/`](equipos/) | Una carpeta por equipo | **Donde suben todo lo que construyan** |

> Algunas cifras del Repositorio vienen de fuentes no oficiales (por ejemplo, la Encuesta Nacional de Egresados de la UVM). Están marcadas así en el CSV: úsenlas, pero díganlo.

## Lo que deben entregar

**Antes del sábado 14 a las 12:00** (las presentaciones empiezan a las 12:30), en su carpeta de equipo:

1. **Prototipo** funcionando, con al menos un dato del Repositorio dentro → `codigo/`
2. **La prueba**: un uso real por alguien fuera del equipo, o una evidencia similar → `evidencia/`
3. **El pitch**: el deck de su solución (problema, usuario, camino, evidencia y modelo de negocio) → `deck/`
4. **Lámina de método**: su comparación contra la Ruta Base (carrera tradicional, técnica o diplomado) → `deck/`

Lo que no esté en el repositorio a las 12:00 no se evalúa.

**La regla de oro:** cada equipo trabaja solo dentro de su propia carpeta. No modifiquen archivos de otros equipos ni las bases del track.

## Cómo crear su carpeta

1. Copien `equipos/_plantilla-equipo/` y renómbrenla con el nombre de su equipo, en minúsculas y con guiones: `equipos/los-sin-titulo/`.
2. Llenen el `README.md` de su carpeta (integrantes, problema, solución, cómo correr el prototipo).
3. Suban todo dentro de su carpeta:

```
equipos/<nombre-de-su-equipo>/
├── README.md        ← quiénes son y qué construyeron
├── deck/            ← pitch y lámina de método (PDF obligatorio; también pueden subir el original)
├── codigo/          ← el código del prototipo, o un enlace a su propio repositorio
├── datos/           ← los datos que usaron, incluidos los del Repositorio
└── evidencia/       ← capturas, notas de la prueba con usuarios, resultados
```

### ¿Su código ya vive en otro repositorio?

No hay problema. Pongan el enlace en el `README.md` de su carpeta y asegúrense de que sea **público** (o den acceso a los organizadores) antes del cierre. El deck sí debe estar aquí, en `deck/`.

### Cómo subir sus archivos

**Opción A: desde la página de GitHub (la más rápida)**

1. Hagan un *fork* de este repositorio (botón **Fork**, arriba a la derecha).
2. En su fork, entren a `equipos/`, den clic en **Add file → Upload files** y arrastren su carpeta.
3. Den clic en **Contribute → Open pull request** para mandarnos su entrega.

**Opción B: desde la terminal**

```bash
git clone https://github.com/<su-usuario>/EdTech.git
cd EdTech
cp -r equipos/_plantilla-equipo equipos/<nombre-de-su-equipo>
# ...trabajen dentro de su carpeta...
git add equipos/<nombre-de-su-equipo>
git commit -m "Entrega: <nombre-de-su-equipo>"
git push
```

Y abran un *pull request* hacia este repositorio. Pueden mandar varios: cuenta el último que llegue antes de las 12:00.

### Reglas de la carpeta

- Trabajen **solo** dentro de su carpeta.
- Nada de contraseñas, llaves de API ni archivos `.env`.
- Nada de datos personales de las personas que probaron su prototipo sin su permiso. Si son menores de edad, necesitan el consentimiento de sus padres o tutores.
- Archivos de más de 50 MB (videos, por ejemplo): súbanlos a Drive o YouTube y dejen el enlace.

## Rúbrica

| Criterio | Peso |
|---|---|
| Problema, usuario y evidencia | 20% |
| Calidad de la solución e innovación | 20% |
| Uso significativo de tecnología | 20% |
| Prototipo + experimentación | 20% |
| Impacto, factibilidad y continuidad | 15% |
| Pitch + demo | 5% |

En empate gana **Prototipo + experimentación**, luego **Problema, usuario y evidencia**.

---

¿Dudas? Busquen a Daniel González León (Workbliss HUB) en el evento.
