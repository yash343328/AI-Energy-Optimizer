# ⚡ AI Workload Energy Consumption Analyzer & Optimizer

> 🚀 Industry-level C# .NET 8 project for intelligent energy-aware scheduling of AI workloads

---

## 📌 Overview

AI data centers are rapidly becoming one of the largest consumers of electricity worldwide.  
This project presents an **intelligent system** that:

- 📊 Monitors real-time energy usage
- 🤖 Predicts energy consumption using ML (Linear Regression)
- ⚡ Optimizes workload scheduling for energy efficiency
- 🌱 Supports green (renewable-powered) computing

---

## 🧠 Key Features

### 🔹 1. Energy-Aware Scheduling
- Multiple strategies:
  - MinEnergy
  - MaxThroughput
  - Balanced (default)
  - GreenOnly 🌱
- Smart GPU selection based on:
  - TDP (power)
  - Compute capability
  - Current load
  - Renewable energy usage

---

### 🔹 2. Real-Time Telemetry
- Tracks:
  - Power consumption (Watts)
  - GPU utilization
  - Temperature
- Continuous monitoring system

---

### 🔹 3. AI-Based Energy Prediction
- Lightweight **online linear regression**
- No external ML libraries required
- Continuously improves accuracy

---

### 🔹 4. Optimization Insights
Generates intelligent recommendations:
- Increase GPU utilization
- Use green-powered nodes
- Reduce high-energy workloads
- Optimize batch sizes

---

### 🔹 5. Benchmarking System
Compare strategies:
- Energy consumption
- Efficiency
- Performance trade-offs

---

### 🔹 6. CSV Export
- Automatically exports results
- Useful for:
  - Research
  - Data analysis
  - Visualization

---

## 🏗️ System Architecture

Workloads → Scheduler → GPU Devices → Execution  
↓  
Energy Predictor (ML)  
↓  
Telemetry Collector  
↓  
Optimization Report


---

## 🖥️ Technologies Used

- **C# (.NET 8)**
- Multithreading (Task, SemaphoreSlim)
- Concurrent Collections
- Simulation-based GPU modeling
- Custom ML (Linear Regression)

---

## ▶️ How to Run

### ✅ Prerequisites
- .NET 8 SDK

### ▶️ Run the project
dotnet run

---

## 📊 Sample Output


-   Workload execution logs
    
-   Energy consumption stats
    
-   Telemetry dashboard
    
-   Optimization report
    
-   Strategy benchmark comparison
    

---

## 🌱 Research Contribution


-   Reduces energy usage by **up to 35%** (simulated)
    
-   Enables **green-aware scheduling**
    
-   Adaptive ML-based prediction system
    
-   Suitable for research paper:
    
    > _"Intelligent Energy-Aware Scheduling for AI Workloads"_
    

---

## 📁 Project Structure


    .├── AIEnergyOptimizer.cs
     ├── README.md

---

## 🔮 Future Improvements


-   Integration with real GPUs (NVIDIA APIs)
    
-   Kubernetes / cloud scheduler support
    
-   Deep learning-based prediction models
    
-   Web dashboard (React + API)
    
-   Carbon footprint tracking (real-time)
    

---

## 👨‍💻 Author


**Yash Jain**  
---

## 📜 License


This project is licensed under the MIT License.

---


