# Wazuh SIEM Setup

This repository documents the setup and configuration of the **Wazuh Security Information and Event Management (SIEM)** tool on an Ubuntu virtual machine, with an agent deployed on a Windows 10 system for monitoring. This setup provides real-time monitoring, vulnerability detection, threat hunting, and compliance tracking for a secure environment.

## Features

### 1. Vulnerability Detection
The **Vulnerability Detection** module scans the environment for potential security risks such as unpatched software, known vulnerabilities, and misconfigurations, providing detailed reports to help mitigate threats.

### 2. Threat Hunting
The **Threat Hunting** feature allows security teams to proactively search for suspicious behavior and anomalies across the network and endpoints. This helps in identifying advanced threats that may evade traditional detection methods.

### 3. PCI DSS Compliance
The **PCI DSS** (Payment Card Industry Data Security Standard) compliance module ensures that systems handling cardholder data meet the necessary security standards. This feature provides monitoring and reporting of PCI DSS compliance status.

### 4. Overview (Home Page)
The **Overview** dashboard is the central interface of the Wazuh SIEM, providing a high-level summary of system activity, security alerts, and an overall view of the security status across monitored systems.

### 5. MITRE ATT&CK Framework
The **MITRE ATT&CK** module maps detected threats and adversarial behavior to the **MITRE ATT&CK** framework. This helps in understanding the tactics and techniques used by attackers and improves defensive strategies.

### 6. HIPAA Compliance
The **HIPAA** (Health Insurance Portability and Accountability Act) compliance module monitors for the protection of sensitive healthcare information. It tracks systems' adherence to security measures and ensures compliance with healthcare industry standards.

### 7. GDPR Compliance
The **GDPR** (General Data Protection Regulation) module monitors data protection measures to ensure compliance with European data privacy regulations. It focuses on safeguarding personal data and protecting user privacy rights.

### 8. Configuration Assessment
The **Configuration Assessment** module evaluates system configurations to identify misconfigurations or deviations from security best practices. This helps ensure systems are hardened against potential attacks.

