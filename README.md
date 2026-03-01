# Agentic AI for Finance - Modification Project

This repository contains the reproduced and modified `nanobot` agentic system. To address the infrastructure bottlenecks and Rate Limit errors (Code 429) found in public free-tier APIs, the system has been modified to utilize the **DeepSeek API** for enhanced stability, lower latency, and cost-effectiveness.

## 🛠️ Installation
1. Ensure you have Python 3.14+ installed on Windows.
2. Clone this repository.
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
## 🚀 Configuration & Run Steps
1. Locate the config.example.json file in this repository.
2. Rename it to config.json and move it to your local ~/.nanobot/ directory.
3. Replace the masked API Key (sk-***) with your actual DeepSeek API key.
4. Run the agent in your terminal to verify the environment:
nanobot agent -m "Hello, please verify your environment and create a test report."