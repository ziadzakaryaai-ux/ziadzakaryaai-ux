<div align="center">

<!-- Header Banner -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0f0f,50:1a1a2e,100:e63946&height=200&section=header&text=Ziad%20Ahmed&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=AI%20%26%20Data%20Engineering%20%7C%20ML%20Systems%20Builder&descAlignY=58&descColor=e63946&animation=fadeIn" />

<!-- Typing animation -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=600&size=22&pause=1000&color=E63946&center=true&vCenter=true&width=600&lines=Building+end-to-end+ML+pipelines;Turning+raw+data+into+production+systems;Mechanical+Eng+→+AI+Engineering;Predictive+Maintenance+%7C+Clinical+AI+%7C+Analytics" alt="Typing SVG" />
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ziad%20Ahmed-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ziad-ahmed)
[![GitHub](https://img.shields.io/badge/GitHub-ziadzakaryaai--ux-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ziadzakaryaai-ux)
[![Email](https://img.shields.io/badge/Email-ziad.zakarya.ai%40gmail.com-e63946?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ziad.zakarya.ai@gmail.com)
[![Location](https://img.shields.io/badge/Cairo-Egypt-FF6B35?style=for-the-badge&logo=googlemaps&logoColor=white)](https://maps.app.goo.gl/cairo)

</div>

---

## `> whoami`

```python
ziad = {
    "role"       : "AI & Data Engineering Intern Candidate",
    "university" : "Ain Shams University — Mechanical Engineering (2025–2029)",
    "trajectory" : "Mech Eng → AI Engineering",
    "focus"      : ["ML Pipelines", "Predictive Systems", "Data Engineering", "Full-Stack ML Apps"],
    "building"   : "End-to-end ML systems that solve real industrial & clinical problems",
    "status"     : "Open to internships & GIT programs in Cairo 🚀"
}
```

---

## `> ls ./projects`

<details>
<summary><b>🔧 Predictive Maintenance — Bearing Fault Detection & RUL Prediction</b></summary>

<br/>

> **Industrial ML pipeline** for bearing fault detection and Remaining Useful Life prediction from vibration sensor streams.

| Metric | Value |
|---|---|
| Dataset | NASA IMS Bearing |
| Features Engineered | **140** time-domain & frequency-domain features per snapshot |
| Classifier F1 Score | **99.49%** (100% Precision, 98.99% Recall) |
| Anomaly Detector F1 | **0.9467** (Isolation Forest, zero labeled failures) |
| RUL Regressor R² | **0.64** |
| Pipeline Coverage | Raw signal ingestion → feature extraction → training → real-time inference |

**What it does:**
- Streams 984 sensor snapshots through 3 concurrent models in real-time
- Outputs `Critical / Warning / Stable` classifications with configurable thresholds
- 12-panel monitoring dashboard: signal traces, degradation probability curves, RUL projections

**Stack:** `Python` `scikit-learn` `NumPy` `Pandas` `SciPy` `Matplotlib` `Seaborn`

[![Repo](https://img.shields.io/badge/View%20Repo-181717?style=for-the-badge&logo=github)](https://github.com/ziadzakaryaai-ux/predictive-maintenance-motors)

</details>

<details>
<summary><b>🏥 ICU Patient Deterioration Risk Prediction System</b></summary>

<br/>

> **Clinical ML pipeline** for predicting ICU patient deterioration from vital sign time-series — grounded in validated medical scoring frameworks.

| Metric | Value |
|---|---|
| Features Engineered | **130+** clinically-motivated features |
| Feature Types | Rolling stats (6h/12h), OLS trend slopes, NEWS2 components, Shock Index, Pulse Pressure |
| Best AUROC | **~0.99** |
| Best Recall | **~0.98** |
| Validation | 5-fold stratified cross-validation |
| Threshold Tuning | 0.32 — optimized for missed-deterioration avoidance |

**What it does:**
- Three-tier alert engine: `Low / Medium / High` risk with escalation pathways
- SHAP-driven per-patient explanations for clinical transparency
- Interactive Streamlit dashboard: 6-panel vital trend charts + population risk distribution

**Stack:** `Python` `scikit-learn` `NumPy` `Pandas` `Matplotlib` `Streamlit` `SHAP`

[![Repo](https://img.shields.io/badge/View%20Repo-181717?style=for-the-badge&logo=github)](https://github.com/ziadzakaryaai-ux/ICU-Vital-Signs-Anomaly-Detection-project)

</details>

<details>
<summary><b>💰 Personal Finance Analyzer — Live Streamlit Dashboard</b></summary>

<br/>

> **Full-stack data app** deployed to Streamlit Cloud — personal expense tracking with intelligent anomaly detection.

**What it does:**
- Dynamic period/category filtering with real-time KPI summaries
- Statistical outlier detection: `mean + 1.8× std` — flags anomalous spending automatically
- 3-month rolling averages for trend visibility
- Full ownership: CSV ingestion → analysis → Streamlit Cloud deployment

**Stack:** `Python` `Pandas` `NumPy` `Matplotlib` `Streamlit`

[![Live App](https://img.shields.io/badge/Live%20App-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://finance-analyzer.streamlit.app)
[![Repo](https://img.shields.io/badge/View%20Repo-181717?style=for-the-badge&logo=github)](https://github.com/ziadzakaryaai-ux/finance-analyzer)

</details>

---

## `> cat skills.json`

```json
{
  "languages": {
    "Python": "Intermediate",
    "SQL": "Basic"
  },
  "ml_and_data": [
    "scikit-learn", "Feature Engineering", "Time-Series Modeling",
    "Anomaly Detection", "SHAP (Explainability)", "Signal Processing",
    "Statistical Analysis", "Data Pipelines"
  ],
  "libraries": ["Pandas", "NumPy", "SciPy", "Matplotlib", "Seaborn", "Streamlit"],
  "concepts": ["Machine Learning", "OOP", "Predictive Modeling", "End-to-End ML"],
  "tools": ["Git", "GitHub", "VS Code", "Microsoft Excel"],
  "deployment": ["Streamlit Cloud"]
}
```

---

## `> cat stack.md`

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

</div>

---

## `> cat roadmap.md`

```
[✅] Python Fundamentals & OOP
[✅] NumPy / Pandas / Matplotlib
[✅] scikit-learn ML Pipelines
[✅] Feature Engineering (Time-Series, Frequency-Domain)
[✅] Anomaly Detection (Isolation Forest)
[✅] Model Explainability (SHAP)
[✅] Streamlit Deployment
[🔄] SQL & Database Engineering
[🔄] Deep Learning (LSTM / TCN for RUL)
[🔄] MLOps & Model Monitoring
[📌] Full-Stack AI Engineering
```

---

## `> cat github_stats.md`

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=ziadzakaryaai-ux&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=e63946&icon_color=e63946&text_color=c9d1d9" />
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ziadzakaryaai-ux&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=e63946&text_color=c9d1d9" />

</div>

---

<div align="center">

### 📬 Let's connect

*First-year ME student building AI systems that work in the real world.*
*Actively seeking internships & GIT programs in Cairo.*

[![LinkedIn](https://img.shields.io/badge/Connect%20on%20LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ziad-ahmed)
[![Email](https://img.shields.io/badge/Send%20an%20Email-e63946?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ziad.zakarya.ai@gmail.com)

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:e63946,50:1a1a2e,100:0f0f0f&height=120&section=footer" />

</div>


-->
