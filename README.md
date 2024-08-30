# Bulk Path Traversal Scanner

This **Bulk Path Traversal Scanner** designed for educational purposes and testing within corporate environments. It automates the process of scanning multiple domains with a set of payloads to identify potential path traversal vulnerabilities.

⚠️ **Disclaimer** ⚠️

Intended only for educational and testing in corporate environments. https://twitter.com/nav1n0x/ and https://github.com/nav1n0x takes no responsibility for the code, use at your own risk. Do not attack a target you don't have permission to engage with.

**About Script**: 

This script automates the process of scanning multiple domains with a set of payloads to identify potential path traversal vulnerabilities. The script works by sending HTTP requests with various payloads to the specified domains, using random user-agents, and processes them in batches to manage load. Successful findings are logged for further verification. However, users are cautioned that the tool may produce false positives and should verify results using additional tools like Burp Suite.

**Futures**: 

The script includes features like configurable batch size, delay, timeout, and retry attempts, making it a flexible tool for large-scale testing. However, users are cautioned that the tool may produce false positives and should verify results using additional tools like Burp Suite.

**Usage**: `scanner.py [-h] -d DOMAINS -p PAYLOADS [-b BATCH_SIZE] [-bd BATCH_DELAY] [-t TIMEOUT] [-r RETRY_COUNT] [-h HELP]`

![image](https://github.com/user-attachments/assets/201a36e1-b4c0-46ed-80fe-2f8fb678e95d)
