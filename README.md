## QUICK & DIRTY MALWARE ANALYSIS

This repository contains documents relating to a malware analysis conducted on 7/30/2020. The analysis was conducted for the purpose of finding correlations in attack patterns being observed against a specific target to see if any of the attacks are related. 

## BACKGROUND

1. These samples were obtained via an email received from an infected mail account. 
2. The email account which sent the sample was trusted by the recipient.
3. The email which contained the malicious attachment was a reply to a legitimate email thread between the two parties.
4. The sender was notified and awknoledged that this account had been compromised. 
5. Emails from the compromised sender were targetted to all of his contacts, not just specific ones.

## NOTES

1. All malicious samples have been removed and replaced with their hash values for security reasons.
2. The machine used is a Windows 7 Professional SP1 Build 7601 on bare-metal.
3. The username used was TESTER. 
4. The hostname used was SANDBOX.
5. All indicators of compromise detected were identified as belonging to the Emotet family of Trojan.
6. Emotet is a versatile trojan initially designed for information theft, remote persistance, ransomware delivery, and botnet management.
7. Emotet propagates primarily through infected email attachments and phishing campaigns.
 
## THEORY

1. I do not believe this campaign is part of an attack aimed at a specific organization.
2. I believe the attackers are exploiting their position in low-level supply chain companies to send as many malicious emails as possible to as many companies as possible from a trusted source.
3. I believe the attackers have access to legitimate, trusted email accounts and leverage this very well in subtle ways.
4. The technological complexity of this campaign appears to be average.
5. The social engineering complexity of this campaign is well above average. 
6. This campaign primarily relies on human elements to infect a target rather than technical vulnerabilities.

## DEFENSE

1. Organizational commitment to training.
2. Due dilligence on an individual level.
3. Communication and collaboration between vested parties when compromise is detected.