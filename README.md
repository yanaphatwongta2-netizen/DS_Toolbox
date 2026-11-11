# DS_Toolbox

Repository สำหรับจัดเก็บงานและทดลองทำงานด้าน Data Science ในรายวิชา
1145100 Data Science Toolbox โดยใช้ Python, Jupyter Notebook และไลบรารีสำหรับ
จัดการ วิเคราะห์ และแสดงผลข้อมูล

## เริ่มต้นใช้งาน

### สิ่งที่ต้องมี

- Git
- Python 3.12
- [uv](https://docs.astral.sh/uv/)

### ติดตั้งสภาพแวดล้อม

เปิด terminal ในโฟลเดอร์ repository แล้วรัน:

```powershell
uv sync
```

ตรวจสอบว่าไลบรารีหลักพร้อมใช้งาน:

```powershell
uv run python -c "import pandas, duckdb, plotly, streamlit; print('พร้อมใช้งาน')"
```

เปิด JupyterLab ด้วย environment ของโครงการ:

```powershell
uv run jupyter lab
```

## โครงสร้าง repository

- `app/` — แอปพลิเคชันและเครื่องมือสำหรับนำเสนอผลการวิเคราะห์
- `notebooks/` — Jupyter Notebooks สำหรับทดลองและวิเคราะห์ข้อมูล
- `src/` — โค้ด Python ที่นำกลับมาใช้ซ้ำได้
- `environment.yml` และ `pyproject.toml` — รายการ dependencies ของโครงการ
- `uv.lock` — เวอร์ชัน dependencies ที่ uv ล็อกไว้

## ผู้จัดทำ

- ชื่อ–สกุล: [ญาณพัทธ์ วงศ์ตา]
- รหัสนักศึกษา: 67114540134
