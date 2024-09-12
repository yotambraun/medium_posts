# 🚦 Urban Traffic Flow Optimization with Genetic Algorithms 🧬

## 🌟 Project Overview
This project tackles the complex challenge of optimizing urban traffic flow using the power of genetic algorithms. By fine-tuning traffic light timings, we aim to reduce congestion and improve overall traffic movement in a simulated city environment.

##  🚀 Key Features

🏙️ Simulated city environment (20x20 grid)
🚥 Dynamic traffic light system
🚗 Realistic car movement simulation
🧬 Multi-objective genetic algorithm optimization
📊 Comprehensive data visualization

##  🔧 Technologies Used

Python 3.x
NumPy
Matplotlib
DEAP (Distributed Evolutionary Algorithms in Python)
Seaborn

##  📊 Results
After running the genetic algorithm for 60 generations:

🔼 10.52% improvement in best traffic flow
🔽 37.58% reduction in average congestion

## 📈 Visualizations
The project generates several insightful visualizations:

Traffic Flow Improvement Over Generations
Congestion Reduction Over Generations
Pareto Front: Traffic Flow vs. Congestion
Best Traffic Light Timings Heatmap
Distribution of Traffic Flow and Congestion

## 🧠 How It Works

City Simulation: We create a 20x20 grid city with 4 intersections and randomly moving cars.
Genetic Algorithm:

Chromosome: Represents traffic light timings for each intersection
Fitness Function: Evaluates based on total car movement and congestion levels
Selection: Uses NSGA-II for multi-objective optimization
Crossover & Mutation: Implements two-point crossover and uniform integer mutation


Optimization: The GA runs for 60 generations, continuously improving traffic light timings.
Analysis: We generate detailed statistics and visualizations to understand the optimization process and results.