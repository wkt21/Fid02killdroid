
<div align="center">
  <img width="1024" height="1024" alt="Fido2KillDroid Logo" src="https://github.com/user-attachments/assets/ff117254-6731-4794-aeb0-709c3c90ef79" />
  <h1>Fido2KillDroid 🔐💣</h1>
  <p><strong>Insert. Tap. Vanish.</strong> Your data obeys.</p>
  <p>A stealth self‑destruct protocol for Android & Termux powered by FIDO2 security keys and biometric triggers.</p>
</div>

---

<div align="center">

![Stars](https://img.shields.io/github/stars/wkt12/Fido2KillDroid)
![Forks](https://img.shields.io/github/forks/wkt12/Fido2KillDroid)
![Issues](https://img.shields.io/github/issues/wkt12/Fido2KillDroid)
![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Status](https://img.shields.io/badge/status-Active-success)
![Tech](https://img.shields.io/badge/python-3.11-blue.svg)

<br><br>

<a href="https://github.com/sponsors/wkt12">
  <img src="https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&color=ff69b4" alt="Sponsor"/>
</a>

</div>

---

## 🔐 Overview

**Fido2KillDroid** is a secure vault‑destruction protocol triggered by a FIDO2 device tap.  
It combines rapid encryption, compression, and secure deletion of sensitive vault contents.

Designed for scenarios requiring **fast, authenticated, irreversible data obliteration**, it leverages hardware‑backed security and robust cryptography to ensure zero recoverable residue.

---

## 🧩 Features

- **FIDO2 Key Challenge + Touch Listener**  
  Hardware‑backed authentication triggers the destruction sequence.

- **AES‑Encrypted `.7z` Vaults**  
  All data is compressed and encrypted before deletion.

- **Full Filesystem Compression**  
  Targets: `/sdcard`, `/data`, `/system`, `/vendor`.

- **Hidden Trigger Log**  
  Execution history stored in `.trigger_log.txt`.

- **Optional Biometric Integration**  
  Fingerprint unlock → destruction authorization.

- **Zero‑Residue Secure Deletion**  
  Ensures no recoverable traces remain.

---

## 📦 Usage

1. **Connect FIDO2 Device**  
   Ensure your FIDO2 key is recognized by Android or Termux.

2. **Configure Vault**  
   Place files you want protected inside your vault directory.

3. **Run Protocol**
   ```bash
   python fido_trigger.py
## 📦 Usage

1. **Connect FIDO2 Device**  
   Ensure your FIDO2 key is recognized by Android or Termux.

2. **Configure Vault**  
   Place files you want protected inside your vault directory.

3. **Run Protocol**
   ```bash
   python fido_trigger.py


1. On FIDO2 Tap• Filesystem compressed
• Archive encrypted
• Original data securely destroyed

2. Output
Encrypted snapshot saved as:backup/vault_<timestamp>.7z.enc

3. Logs
Execution history appended to:logs/.trigger_log.txt



---

🖼️ Self‑Destruct Touch Image

Use this image as a touchscreen panic button or vault‑destruction trigger in your security workflows.

#!/bin/bash
echo "Self-destruct image downloaded as self_destruct.svg"


[Looks like the result wasn't safe to show. Let's switch things up and try something else!]

Instant download:

bash download_self_destruct_img.sh


---

📜 MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the “Software”), to deal
in the Software without restriction…

(Full MIT license text preserved.)
