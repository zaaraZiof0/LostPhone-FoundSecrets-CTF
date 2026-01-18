# 🔍 Lost Phone, Found Secrets - CTF

[![Difficulty](https://img.shields.io/badge/Difficulty-Medium-red?style=for-the-badge)](https://github.com)
[![Category](https://img.shields.io/badge/Category-Digital%20Forensics-blue?style=for-the-badge)](https://github.com)
[![Points](https://img.shields.io/badge/Points-500-green?style=for-the-badge)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Android-brightgreen?style=for-the-badge)](https://github.com)

> An advanced Android mobile forensics CTF challenge featuring anti-forensics techniques, deleted data recovery, and timeline correlation.

---

## 📱 The Story

The sun sets over the Puttalam Lagoon in Sri Lanka, casting long shadows across the water. Local fishermen report finding an abandoned smartphone near the shoreline, partially submerged and showing signs of deliberate damage.

The phone belongs to **Kasun Perera**, a senior logistics coordinator at **Ceylon Logistics Ltd.**, one of Sri Lanka's largest shipping companies. Three days ago, Kasun vanished without a trace after being suspected of leaking classified cargo manifests to competitors information that could compromise national security and cost millions.

When authorities recovered his Android phone, initial analysis revealed troubling signs:
- The device had been remotely factory reset
- Multiple anti-forensics tools were executed
- System timestamps appeared manipulated
- Critical data had been systematically deleted

But digital evidence is never truly gone. As a member of the **Digital Forensics Response Unit (DFRU)**, you've been assigned to this high-priority case. The phone holds secrets—deleted WhatsApp messages, GPS trails, memory fragments clues that could reveal:

- **Where** did Kasun send his final message from?
- **What** was he trying to hide?
- **Who** was he communicating with?

The clock is ticking. Corporate espionage, data leaks, and a missing person all pieces of a puzzle scattered across corrupted filesystems and manipulated logs.

**Your mission:** Analyze the forensic artifacts, defeat the anti-forensics techniques, and uncover the truth hidden in the digital shadows.

---

## 🎯 Challenge Overview

**Category:** Digital Forensics / Mobile Forensics  
**Difficulty:** Medium (Medium Level)  
**Flag Format:** `ZeroX{Location_keyword}`  
**Estimated Time:** 4-8 hours  
**Points:** 500

---

## 📥 Download Challenge

**Challenge Package:** [Download from MEGA.nz](https://mega.nz/file/nANR2TrC#oMf38h4oZG869nLhvPCYK64AsJ77XZgCyI9_QWg71ZI)

**Size:** 71 MB (Compressed)  
**Format:** ZIP Archive  
**Password:** None


---


## 🛠️ Required Skills

### Essential
- Android filesystem forensics
- SQLite database analysis
- Deleted data recovery techniques
- Timeline reconstruction
- Memory forensics

### Advanced
- Write-Ahead Logging (WAL) forensics
- Monotonic counter analysis
- GPS timestamp correlation
- Anti-forensics detection
- Multi-artifact correlation

---


## 🚩 Flag Submission

Once you've completed your analysis:

**Submit your flag via LinkedIn:** [Sithum Shihara (Zaara)](https://www.linkedin.com/in/sithum-shihara-zaara)

**Flag Format:** `ZeroX{Location_keyword}`

Example: `ZeroX{Colombo_example}` *(not the real flag!)*

⚠️ **Note:** 
- Flag is **case-sensitive**
- Location must be a Sri Lankan city name (proper capitalization)
- Keyword must be lowercase
- No spaces in the flag

---

## 💡 Hints (If You Get Stuck)

<summary><b>⏰ Hint 2: Timeline Analysis</b></summary>

System timestamps can be manipulated, but some Android timekeeping mechanisms cannot be easily faked. Look for monotonic counters (time since boot) in the GPS cache database. The `elapsed` field is your friend.

Correlate these timestamps with system event logs to find inconsistencies.
</details>

---

## 🏆 Challenge Difficulty

**Difficulty Rating:** ⭐⭐⭐⭐⭐⭐⭐⭐ (8/10)

### Skill Breakdown
- **Filesystem Forensics:** ⭐⭐⭐⭐⭐⭐ (6/10)
- **Database Analysis:** ⭐⭐⭐⭐⭐⭐⭐ (7/10)
- **Timeline Correlation:** ⭐⭐⭐⭐⭐⭐⭐⭐⭐ (9/10) - Most challenging!
- **Memory Forensics:** ⭐⭐⭐⭐ (4/10)
- **Overall Complexity:** Expert / Advanced

**Expected Solve Time:** 4-8 hours for experienced forensic analysts

---



## 🔒 Challenge Integrity

⚠️ **Spoiler Warning:** This challenge is designed to be solved without external solutions.

Please refrain from:
- Sharing solutions publicly before attempting yourself
- Posting complete walkthroughs without spoiler warnings
- Distributing the flag without proper context

**Fair Play:** This challenge tests real forensic skills. Use hints sparingly and try to solve independently first!

---

## 📊 Challenge Statistics

| Metric | Value |
|--------|-------|
| **Artifact Size** | 171 MB (uncompressed) |
| **File Types** | 10 different forensic artifacts |
| **Anti-Forensics Techniques** | 6 major techniques |
| **Skills Tested** | 8 core forensic skills |
| **Expected Difficulty** | Medium Level |
| **Real-World Applicability** | High - based on actual techniques |


---

## 👨‍💻 Challenge Author

**Created by:** ZeroX CTF Team  
**Submitted by:** [Sithum Shihara (Zaara)](https://www.linkedin.com/in/sithum-shihara-zaara)  
**Version:** 1.0  
**Release Date:** January 2026  
**Country:** Sri Lanka 🇱🇰

---

## 📜 License & Usage

### For Players
- ✅ Free to download and solve
- ✅ Share your experience (no spoilers!)
- ✅ Learn and practice forensic techniques

### For Educators
- ✅ Free for educational and training purposes
- ✅ Attribution required
- ✅ Cannot be used for commercial competitions without permission

### For CTF Organizers
- ✅ Can be used in CTF competitions
- ✅ Attribution required: "Challenge by ZeroX CTF Team"
- ✅ Modifications allowed
- ✅ Contact for commercial use

---

## 📞 Contact & Support

### Submit Your Flag
🔗 **LinkedIn:** [Sithum Shihara (Zaara)](https://www.linkedin.com/in/sithum-shihara-zaara)

### Questions?
- Check the hints above first
- Search for Android forensics tutorials
- Study SQLite database analysis
- Learn about monotonic timers in Android

### Feedback
Found an issue? Have suggestions? Connect via LinkedIn!

---

## 🎯 Quick Start Guide

```bash
# 1. Download the challenge
wget https://mega.nz/file/nANR2TrC#oMf38h4oZG869nLhvPCYK64AsJ77XZgCyI9_QWg71ZI

# 2. Extract the archive
unzip 'Lost Phone, Found Secrets.zip'

# 3.  Start analyzing!

# 5. When you find the flag, submit via LinkedIn!
```



## ⚡ Ready to Begin?

**Download the challenge now and start your investigation!**

🔗 **[Download from MEGA.nz](https://mega.nz/file/nANR2TrC#oMf38h4oZG869nLhvPCYK64AsJ77XZgCyI9_QWg71ZI)**

🚩 **Submit your flag:** [LinkedIn - Sithum Shihara (Zaara)](https://www.linkedin.com/in/sithum-shihara-zaara)

---

## 🙏 Acknowledgments

Special thanks to:
- The Sri Lankan cybersecurity community
- Android Open Source Project (AOSP)
- Digital forensics researchers worldwide
- CTF challenge creators who inspire us

---

<div align="center">

### 🔍 **The truth is buried in the data. Can you find it?**

**Flag Format:** `ZeroX{Location_keyword}`

[![Download](https://img.shields.io/badge/Download-MEGA.nz-red?style=for-the-badge&logo=mega)](https://mega.nz/file/nANR2TrC#oMf38h4oZG869nLhvPCYK64AsJ77XZgCyI9_QWg71ZI)
[![Submit](https://img.shields.io/badge/Submit%20Flag-LinkedIn-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/sithum-shihara-zaara)

**Good luck, forensic analyst.** 🇱🇰

---

*Made with ❤️ by ZeroX CTF Team | Sri Lanka 🇱🇰*

</div>
