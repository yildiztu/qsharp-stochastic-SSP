# qsharp-stochastic-SSP

The goal is to find the shortest path between a start node and a goal node in a graph, while taking into account the uncertain edge weights.

The objective function is uncertain and minimizes the total distance traveled while satisfying constraints such as vehicle capacity and customer delivery time windows. The problem is formulated as a graph where each node represents a customer and each edge represents a potential delivery route. The algorithm starts with an initial solution and iteratively improves it by moving to a new point in the solution space which is expected to result in a better solution. The result is printed as a matrix where each element represents a scheduled edge between two customers.
