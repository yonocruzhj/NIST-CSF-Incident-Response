<h1>Incident Response using NIST CSF</h1>

<h2>Description</h2>
This project provides a detailed incident report analysis of a simulation following the guidelines of the NIST Cybersecurity Framework (CSF). The analysis covers the five core functions of the NIST CSF—Identify, Protect, Detect, Respond, and Recover—to assess, mitigate, and respond to cybersecurity incidents.
<br />


<h2>Goals</h2>
The goal of this project was to create a plan to improve the company's network security following the guidance of the NIST CSF.

<h2>Incident Response Process:</h2>

<p align="center">
Scenario: <br/>
<img src="https://imgur.com/NQqpsQQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

**Incident report analysis**

| Summary | The company experienced a distributed denial of services (DDoS) attack that caused all the network services to stop responding. This was due to the incoming flood of ICMP packets. In order to restore the critical network services and solve the issue, the incident management team blocked the attack and stopped all non-critical network services offline. |  |  |
| :---- | :---- | ----- | ----- |
| Identify | A malicious actor attacked the company with an ICMP flood attack through an unconfigured firewall. As a result, the internal network of the company could not access any network resources. All critical network resources needed to be secured and restored. All non-critical network services had to be temporarily shut down. |  |  |
| Protect | The network security team implemented a new firewall rule to limit the rate of incoming ICMP packets. They implemented a source IP verification on the firewall to check for spoofed IP addresses on incoming ICMP packets. The team implemented a network monitoring software to detect abnormal traffic patterns. Finally, they implemented an IDS/IPS system to filter out ICMP traffic based on suspicious characteristics.  |  |  |
| Detect | The security team implemented monitoring techniques to improve security posture. They implemented a source IP verification on the firewall to check for spoofed IP addresses on incoming ICMP packets. They also implemented a networking monitoring software to detect abnormal traffic and an IDS/IPS.  |  |  |
| Respond | In the case of future incidents, the cybersecurity team will isolate affected systems to mitigate disruption to the company. The incident management team will restore any critical systems that were affected by the attack. Then, the team will analyze network logs to check for abnormal patterns. The incident management team will also report all incidents to upper management and legal authorities. |  |  |
| Recover | In order to recover from a DDoS attack by ICMP flooding, access to critical network resources need to be restored. Critical network services should be the first to be restored. In case of future DDoS attacks, incoming ICMP flood attacks can be blocked at the newly implemented firewall. Then, all non-critical network services should be temporarily stopped to reduce network traffic. After the flood of ICMP packets time out, all non-critical network systems and services can be brought back online. |  |  |


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
