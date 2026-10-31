# Cybersecurity Lab Environment Setup

## 1. Project Overview

This project focuses on setting up a cybersecurity testing lab environment using Oracle VirtualBox and Kali Linux. The lab is designed for ethical hacking practice, cybersecurity testing, and security learning.

## 2. Project Objectives

- Install and configure Oracle VirtualBox.
- Set up Kali Linux as an attacking machine.
- Configure a NAT Network using the 10.0.0.0/24 subnet.
- Assign a static IP address to Kali Linux.
- Enable clipboard sharing and drag-and-drop.
- Configure shared folders.
- Verify internet connectivity.
- Create a virtual machine snapshot.

## 3. Tools Used

- Oracle VirtualBox
- Kali Linux
- 7-Zip
- Windows Host Operating System

## 4. Network Configuration

| Configuration   | Value         |
| --------------- | ------------- |
| Network Type    | NAT Network   |
| Network Address | 10.0.0.0/24   |
| Kali Linux IP   | 10.0.0.3      |
| Subnet Mask     | 255.255.255.0 |
| Default Gateway | 10.0.0.1      |
| DNS Server      | 8.8.8.8       |

## 5. Implementation Steps

1. Downloaded and installed 7-Zip.
2. Downloaded and installed Oracle VirtualBox.
3. Created a NAT Network with the 10.0.0.0/24 subnet.
4. Downloaded and imported Kali Linux into VirtualBox.
5. Configured Kali Linux with the required static IP address.
6. Enabled shared clipboard and drag-and-drop.
7. Configured the shared downloads folder.
8. Tested internet connectivity.
9. Created a Kali Linux virtual machine snapshot.

## 6. Internet Connectivity Testing

The following commands were used to verify network connectivity:

```bash
ip addr
ip route
ping -c 4 8.8.8.8
ping -c 4 google.com
```

## 7. Screenshots

Add your actual screenshots here:

- VirtualBox Installation
- NAT Network Configuration
- Kali Linux VM
- IP Address Configuration
- Internet Connectivity Test
- Clipboard and Drag-and-Drop Settings
- Shared Folder Configuration
- VM Snapshot

## 8. Learning Outcomes

Through this project, I gained practical experience in virtual machine management, network configuration, Kali Linux installation, and cybersecurity lab preparation.

## 9. Conclusion

The cybersecurity testing lab provides an isolated virtual environment for practicing ethical hacking and cybersecurity activities.

**Project:** NetworkWalks Cybersecurity Program
**Module:** WK1-PM1
**Author:** Zakaria Ahmed Barre
