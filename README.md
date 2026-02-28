# Email_auto_classification
Python-powered automation system to extract key data from high-volume email inboxes. Identify "service extension" requests amidst noise, it leverages IMAP and Pandas to transform unstructured text into structured Excel reports. Focuses on improving operational efficiency through automated ETL and data cleaning.

**📌 Project Overview**
Developed during a medical aesthetics industry internship in Singapore, this project addresses the operational challenge of managing high-volume customer service emails. The system automates the identification and extraction of "Service Extension" requests—a paid service ($10 SGD) allowing customers to extend treatment validity.

The Challenge: "Inbox Noise"
The corporate feedback email was a "disaster," cluttered with job applications, general inquiries, complaints, and spam. Manually filtering these to find legitimate extension requests was highly inefficient.

**🚀 Key Features**

Automated Filtering: Leverages Python’s imaplib to scan Gmail inboxes and isolate valid service requests amidst significant "noise" using keyword-based recognition.

Dynamic Data Extraction: Automatically parses unstructured email content to extract critical business fields: Project Name, Purchase Time, Customer Name/Account, and Treatment Balance.
Intelligent Date Range Query: Features an interactive command-line interface allowing users to specify exact date ranges for targeted data retrieval.

ETL Pipeline: Transforms raw email data into structured, analysis-ready formats (Excel/CSV) using Pandas for seamless operational integration.

Traceability: Generates clickable Google Search links based on Message-ID to allow instant access to the original email thread for verification.

**🛠️ Tech Stack**

Language: Python 
Data Processing: Pandas 
Protocols & APIs: IMAP (via imaplib), email.header for decoding 
Automation: Scripting for workflow optimization 

**📈 Business Impact & Professionalism**

Efficiency: Replaced manual inbox sorting with an automated script, drastically reducing processing time(by 90%) and human error(to nearly 0%).
Data-Driven Ops: Converted disorganized text into structured datasets, enabling faster updates to the customer management system.
Scalability: The logic can be easily adapted to identify other intent-based customer communications (e.g., refund requests or booking inquiries).

**⚠️ Security Note**
For security compliance, this repository uses environment variables/placeholder credentials. Actual App Passwords and sensitive user data are never hardcoded in the source files.



