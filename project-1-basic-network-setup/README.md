Project Overview
This project simulates a departmental network using Cisco Packet Tracer. It connects two departments — ACCOUNTS and DELIVERY — using switches and a router, with IP configurations based on the network address . The goal is to demonstrate how to configure inter-VLAN routing and verify connectivity between devices in separate VLANs.

🎯 Objectives
• 	Design a network topology connecting ACCOUNTS and DELIVERY departments
• 	Assign IP addresses, subnet masks, and gateways using 
• 	Configure VLANs for each department
• 	Implement inter-VLAN routing using a router-on-a-stick setup
• 	Connect all devices using correct cabling
• 	Verify connectivity between PCs in both departments using the  command

📚 Inter-VLAN Routing – Theory
In a typical Layer 2 switch environment, devices in different VLANs cannot communicate directly. Inter-VLAN routing allows traffic to pass between VLANs by using a Layer 3 device (usually a router). This project uses the Router-on-a-Stick method, where:
• 	A single physical router interface is divided into multiple subinterfaces, each assigned to a VLAN.
• 	Each subinterface is configured with an IP address and tagged with the appropriate VLAN ID.
• 	The switch port connected to the router is set to trunk mode, allowing multiple VLANs to pass through.
This setup enables PCs in the ACCOUNTS VLAN to communicate with PCs in the DELIVERY VLAN, even though they are logically separated.
