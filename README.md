# Hi, I'm Yingying Sun 👋

**Data Scientist & AI Engineer** based in San Jose, CA.  
I build production-grade agentic AI systems — LangGraph workflows, RAG pipelines, and GEO-optimized content intelligence — with measurable business impact.  
**University of Michigan, Master of Applied Data Science** (4.0 GPA), specializing in Agentic AI and Generative Engine Optimization.

---

## 🛠️ Tech Stack

**AI & GenAI**  
![LangGraph](https://img.shields.io/badge/LangGraph-000000?style=flat&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=python&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-6E40C9?style=flat&logo=openai&logoColor=white)
![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-FF6B6B?style=flat)
![GEO / AIO](https://img.shields.io/badge/GEO_%2F_AIO-0077B5?style=flat)

**Machine Learning**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)

**Data & Cloud**  
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)

**BI & Visualization**  
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat&logo=powerbi&logoColor=black)

---

## 🚀 Featured Projects

### 🤖 [Multi-Agent Editorial & Fact-Verification Loop](https://github.com/ying2sun/MultiAgent-Editorial-Workflow)
A stateful 4-agent LangGraph orchestration pipeline that autonomously drafts, fact-checks, and GEO-optimizes news articles in real time.  
Built with: `LangGraph` · `Pydantic` · `NewsData.io API` · `Streamlit` · `Google Gemini`  
→ **Live Demo:** [Try it here](https://multiagent-editorial-workflow-nx4legyb4hpt8x8ifpuy7s.streamlit.app)

### 📺 [AI-Powered YouTube Video Summarization via RAG & Knowledge Distillation](https://github.com/ying2sun/AI-powered-YouTube-Video-Summarization)
Fine-tuned Flan-T5 using knowledge distillation from Gemini 2.0 to produce cost-free, locally deployable video summaries — validated through ROUGE metrics and a structured human evaluation framework.  
Built with: `Flan-T5` · `RAG` · `FAISS` · `Hugging Face` · `Gemini API`  
→ **Live Demo:** [Hugging Face Spaces](https://huggingface.co/spaces/ying2sun/youtube-video-summarizer-capstone)

---

## 📈 Currently Building

### 🀄 Traditional Chinese GEO Content Pipeline
*English news in → GEO-optimized Hong Kong Traditional Chinese article out — at near-zero inference cost*

A 4-agent system that takes English news articles and produces publication-ready, GEO-formatted Traditional Chinese articles in authentic Hong Kong editorial voice:

`Fetcher` → `Translator` → `Editorial Rewriter (fine-tuned Student)` → `Validator`

The core agent is a **QLoRA fine-tuned Llama 3.1 8B** model, trained via knowledge distillation from a frontier Teacher model, deployed locally via Ollama at **zero marginal inference cost**.

**Key methodological decisions:**
- Train/test distribution alignment — Student trains on machine-translated Chinese input to match production conditions, eliminating distribution mismatch
- Knowledge distillation with synthetic data generation — Teacher model produces GEO-formatted training articles; Student learns to replicate the format and editorial voice
- Three-level evaluation framework: training data quality (AI Judge + human eval + Pearson agreement) → Student model quality in isolation → end-to-end pipeline quality (English → Chinese GEO)
- Cross-model LLM-as-Judge — generator and evaluator are different model families to avoid self-evaluation bias

**Total project budget: under $20** | Built with: `Llama 3.1 8B` · `QLoRA/Unsloth` · `DeepSeek V3.2` · `Ollama` · `OpenRouter`

---

## 📬 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yingying-sun-44869923)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/ying2sun)
