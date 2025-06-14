
# Custom Nuclei Templates

This repository contains custom Nuclei templates for vulnerability scanning.

## Structure
- `cves/`: CVE-specific templates.
- `misconfig/`: Templates for misconfigurations.
- `technologies/`: Technology fingerprinting templates.
- `vulnerabilities/`: General vulnerability templates.
- `workflows/`: Complex workflows combining multiple templates.

## Templates Included
1. **XSS Detection**: Detect basic XSS.
2. **SQL Injection (SQLi)**: Identify potential SQL injection points.
3. **Exposed Admin Panel**: Find publicly accessible admin panels.
4. **CVE-2025-XXXX**: Example CVE detection.
5. **Technology Fingerprinting**: Detect CMS like WordPress, Joomla, etc.

## Usage
Clone this repository and add it to your Nuclei configuration.

```bash
nuclei -ut https://github.com/yourname/custom-nuclei-templates.git
```

Happy Scanning! 🚀
