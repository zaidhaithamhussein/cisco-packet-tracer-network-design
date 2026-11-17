# Multi-Site Network Design — Cisco Packet Tracer

A university networking project modeled in **Cisco Packet Tracer**. The simulation file includes a multi-site network topology with interconnected routers, switches, local networks, wireless access points, end-user devices, and a central server area.

## Network topology

![Network topology](screenshots/network-topology.png)

## Project overview

The topology illustrates:

- Multiple routers connected over a network backbone / WAN-style links.
- Several LAN segments connected through switches.
- End devices including desktop computers, laptops, and printers.
- Wireless access points in multiple LANs.
- A central network segment containing several servers.
- Visible IP-address and subnet annotations.
- An ISP-labeled connection.

**Note:** These observations are based on the visible topology. Specific routing protocols, services, and end-to-end connectivity have not yet been independently verified.

## Files

- `FinalNetworking.pkt` — original Cisco Packet Tracer project file (unchanged).
- `screenshots/network-topology.png` — overview of the topology.

## How to open

1. Install Cisco Packet Tracer from Cisco Networking Academy.
2. Open Packet Tracer, then select **File > Open**.
3. Select `FinalNetworking.pkt` to inspect the topology and device configurations.
4. Use **Simulation** mode or command-line tests such as `ping` to check connectivity.

## Suggested verification before showcasing

- Confirm that representative PCs can reach their default gateways.
- Test traffic between different LANs.
- Check whether the central servers are reachable where intended.
- Review router configuration and routing tables to document the exact routing method.

## Project context

University networking final project. Created as a learning exercise in network topology design and simulation.
