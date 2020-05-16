# Inventory-System-Simulation
The (M, L) inventory system modeled in this simulation has a maximum inventory level of 50 and a reorder point of 30. The inventory is checked at the end of each month. If current inventory levels plus inventory on order is less than 30, a new order is placed. If current inventory plus inventory on order is greater than or equal to 30, no order is placed at the end of the month. The procurement quantity Q in the order is defined by the maximum inventory level (M) minus the current inventory plus inventory on order (I). Backordering is allowed, but it comes at a cost of $4 per item short per month.

Lead time of new orders varies according to a uniform distribution on the interval [0.25, 1.25] months. Time between customer demands is exponentially distributed with a mean of 1/15 month. The size of the demands follows this empirical distribution:

1/2 probability of 1 demand
1/4 probability of 2 demand
1/8 probability of 3 demand
1/8 probability of 4 demand
The starting inventory in the inventory system is 50 units, with no orders outstanding.

The objective of this simulation is to solve for the mean monthly cost of the inventory system. The costs associated with the system are as follows:

Backlog: $4 per item short per month
Holding: $1 per unit in inventory per month
Ordering: $60 per order
Item: $5 per item ordered
Ten replications of the simulation will be generated, and then the long-run mean monthly cost will be estimated by averaging the results across replications. In addition, a 90% confidence interval will be constructed.

If the results from the ten replications lead to a confidence interval wider than $5, the total number of additional replications needed to shrink the confidence interval to $5 will be estimated.
