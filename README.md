ALL-IN-ONE DEVICE SECURITY TOOL

A Python-based, ethical, and legal security utility designed to help users protect their own devices and accounts.
This tool performs four major safety checks:
	1.	Detects suspicious network connections
	2.	Detects potentially harmful or unknown processes
	3.	Checks if your email has appeared in a known data breach (HaveIBeenPwned API)
	4.	Evaluates the strength of a password locally and securely

This project does not perform any hacking activity. It is strictly for personal security, ethical use, and device protection.

⸻

Features

1. Suspicious Network Connection Scanner

Scans active network connections on your device and flags any uncommon or potentially unsafe outbound connections.

2. Suspicious Process Scanner

Searches for processes whose names resemble known malicious or intrusive software.

3. Email Breach Checker

Uses the official HaveIBeenPwned API to check if your email address has appeared in any public data breaches.
Requires the user to provide their own API key.

4. Password Strength Checker

Analyzes a password locally on your device.
No password is uploaded, logged, or transmitted.

⸻

Installation

Install the required Python modules:

pip install psutil requests

Clone or download the project folder, then run the main script:

python security_tool.py


⸻

Configuration

HaveIBeenPwned API Key

For the email breach check to work, you must obtain your own API key:
	1.	Visit the HaveIBeenPwned website
	2.	Create an account
	3.	Generate an API key
	4.	Replace the placeholder in the script:

headers = {"hibp-api-key": "ENTER_YOUR_API_KEY"}

Without a valid key, the breach-checking feature will not work.

⸻

Usage

When you run the program, a menu will appear with the following options:
	1.	Scan suspicious network connections
	2.	Scan suspicious running processes
	3.	Check if your email was in a data breach
	4.	Check password strength
	5.	Exit

Select a number to run the corresponding security check.

⸻

Ethical Use Notice

This tool is designed only for:
	•	Protecting your own device
	•	Detecting possible malware or unauthorized access
	•	Improving your personal cybersecurity

It must not be used for:
	•	Accessing another person’s account
	•	Monitoring another device
	•	bypassing security measures

All use must comply with local laws and ethical standards.

⸻

License

This project can be used, modified, and shared for personal or educational cybersecurity purposes. Commercial use and any malicious application are strictly prohibited.

⸻
	•	A logo or project icon

Just tell me.
