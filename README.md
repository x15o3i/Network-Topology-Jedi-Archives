# 💻 Network-Topology-Jedi-Archives

## 🌐 Overview: Multi-Branch Office Network

Welcome to the Jedi Archives! This repository begins with my first fully completed project in Cisco Packet Tracer, the **Multi-Branch Office Network**.

This project simulates a Wide Area Network (WAN) connecting three geographically separate offices (HQ, Sales, and Warehouse). The primary achievement here is demonstrating **full inter-network connectivity** using meticulously configured **Static Routes**.

## 📂 File Archive

| File Name | Primary Concept Demonstrated | Description | Status |
| :--- | :--- | :--- | :--- |
| **Multi-Branch Office Network.pkt** | **Static Routing (WAN)** | Successfully links three $192.168.x.x$ LANs using an efficient $172.16.x.x /30$ backbone. All branches are fully pingable. | **Complete & Verified** |

---

## ⚙️ Key Skills Demonstrated

* **Static Routing:** Manually configuring six routes across three routers to ensure every network can reach every other network.
* **IP Addressing & Subnetting:** Efficient use of the dedicated **`/30` subnet mask ($255.255.255.252$)** for point-to-point WAN links.
* **Layer 3 Connectivity:** Troubleshooting and resolving interface overlaps and routing issues to achieve end-to-end communication.
* **Cisco IOS Configuration:** Setting interface IPs, clock rates, and saving configurations on Cisco 1941 Routers.

## ✅ Verification

The project is verified by a successful ping from a device in the HQ office to any device in the remote Warehouse office, confirming multi-hop routing is functional.

---
**Next Step:** The next mission in the archives will be to reconfigure this network to use **Dynamic Routing (OSPF)** to replace the static routes!
2.  Navigate to the `packet-tracer-files/` folder.
3.  **Open** any `.pkt` file using Cisco Packet Tracer.
4.  Inspect the **CLI** or **Desktop** tabs on the devices to review the network configurations.

---
**May the packets be with you!**
