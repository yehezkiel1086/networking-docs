# **Network Subnetting and Routing with CIDR and VLSM - Group D15**

## Table of Contents

- [CIDR Configuration on GNS3](#cidr-configuration-on-gns3)
- [VLSM Configuration on CPT](#vlsm-configuration-on-cpt)

## CIDR Configuration on GNS3

### 1. Identify subnets in the topology and label netmasks for each subnet

<img src="./assets/gns3.png" />

### 2. Calculate IP allocation tree based on the subnet aggregation performed

<img src="./assets/cidr_tree.png" />

Based on the calculation, the resulting IP allocation is as follows:

<img src="./assets/cidr_ip.png" />

## VLSM Configuration on CPT

### 1. Identify subnets in the topology and label netmasks for each subnet

![cpt](./assets/cpt.png)

### 2. Calculate the number of clients per subnet

![jumlah_ip_subnet](./assets/jumlah_ip_subnet.png)

### 3. Construct the VLSM Tree

![vlsm_tree](./assets/vlsm_tree.png)

### 4. Allocation of NID, Netmask, and BID for each subnet

![vlsm_ip_subnet](./assets/vlsm_ip_subnet.png)

### 5. Client IP allocation per subnet

![vlsm_ip_client](./assets/vlsm_ip_client.png)

### 6. Routing via routers to connect all subnets

![vlsm_routing_cpt](./assets/vlsm_routing_cpt.png)

> The routing snippet above is only a small portion of the routing configured on each router. For complete details, please refer to the provided `.pkt` file.