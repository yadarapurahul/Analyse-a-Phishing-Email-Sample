# Analyse-a-Phishing-Email-Sample
The The objective of this task is to analyze a suspicious phishing email and identify key red flags commonly used by attackers. This exercise helps develop practical skills in email threat detection, social engineering awareness, and phishing identification — all essential areas in cybersecurity

## 🧰 Tools used:
- Text Editor (view raw email)
- Brower (link inspection)
- Online email header analyzer
---
## 🚩 Identified Phishing Indicators

**1.Spoofed Sender Address**
- The email claims to be from Banco Bradesco, but uses a suspicious domain:  
  `@atendimento.com.br` instead of a legitimate `@bradesco.com.br`.
  
**2.Suspicious Links**
- The main action button uses a link:  
  `https://blog1seguimentmydomaine2bra.me/`  
  which is **not a Bradesco domain** and is likely used for credential harvesting or malware.

**3.Urgent Language**
- The message pressures the user with:  
  “92.990 pontos LIVELO expirando HOJE” (points expiring **today**), a classic urgency tactic.

 **4.Grammar and Spelling Issues**
- There are awkward phrases such as:
  - "Descontos de ate 35%" (missing accent in "até")
  - "Troque seus pontos por milhas aereas" (should be "aéreas")

**5.Fake Branding and Styling**
- Although the email mimics Bradesco’s branding, it includes:
  - Missing or fake image references (e.g., `header.png`)
  - Suspicious HTML with non-standard fonts and links

**6.Social Engineering**
- Exploits desire to avoid losing reward points, luring users into clicking harmful links.

---

## 🧪 Header Analysis

**No original headers provided**, but likely issues (based on structure):
- Mismatch between sender's domain and reply-to.
- Lack of SPF/DKIM authentication.
- IP address might point to a hosting provider not related to Bradesco.

You can analyze headers using tools like:
- (https://mxtoolbox.com/EmailHeaders.aspx)
- (https://toolbox.googleapps.com/apps/messageheader/)

---

## 🚩 Red Flags Identified in Phishing Email ample.txt
**Suspicious Sender Address**
- **From**: banco.bradesco@atendimento.com.br
- **Why it's suspicious**: A legitimate Bradesco email would likely use an official domain like @bradesco.com.br, not a generic or misleading domain like atendimento.com.br (which means "support" in Portuguese — easily abused).
---

## Files Included
- **Phishing Email sample** - Raw Phishing email in HTML
- **Screenshot**- Screenshot of Phishing email header analyzer
- **README.md** - This report
