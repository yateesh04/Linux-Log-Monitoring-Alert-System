# Linux Log Monitoring & Alert System

## Project Overview
The Linux Log Monitoring & Alert System is a Linux system administration project designed to help users view, search, and analyze log files. It identifies important events, including errors, critical messages, and failed login attempts, and generates alerts and summary reports.

The project provides both a menu-driven terminal interface and a local web dashboard.

## Objectives
- Simplify Linux log analysis.
- Detect errors and critical events.
- Identify failed login attempts.
- Generate alert files and summary reports.
- Provide terminal and web-based interfaces.
- Demonstrate practical Linux system administration concepts.

## Technologies Used
- **Operating System:** Ubuntu Linux
- **Virtualization:** Oracle VirtualBox
- **Scripting:** Bash and Linux commands
- **Backend:** Python
- **Frontend:** HTML, CSS, JavaScript
- **Version Control:** Git and GitHub

## Features
- View sample log files.
- Search logs using keywords.
- Analyze error and critical entries.
- Detect failed login attempts.
- Generate and view alerts.
- Generate summary reports.
- Display Linux system information.
- Access available real Linux logs.
- Monitor new matching events while monitoring is running.
- View monitoring information through a local web dashboard.

## Project Structure

```text
linux-log-monitor/
├── alerts/
├── logs/
├── reports/
├── scripts/
├── web/
│   └── index.html
└── server.py
```

## How to Run

1. Start Ubuntu Linux and open a terminal.
2. Navigate to the project directory:

   `cd ~/linux-log-monitor`

3. Start the Python server:

   `python3 server.py`

4. Open a second terminal and run the menu:

   `bash scripts/monitor.sh`

5. Open the dashboard using the local URL printed by the server.

## Testing
The project includes tests for log viewing, keyword searching, failed-login detection, log analysis, alert generation, summary report generation, and monitoring of new matching events.

## Limitations
- Monitoring must be started manually.
- The dashboard runs locally.
- Logs, alerts, and reports are stored in files.
- Database-backed history and email notifications are not implemented.

## Future Enhancements
- Scheduled monitoring.
- Automated backup support.
- Database-backed historical log storage.
- Email or messaging notifications.
- Remote monitoring of multiple Linux systems.

## Conclusion
This project demonstrates how Bash scripting, Linux commands, Python, and web technologies can be combined to create a practical log monitoring and alert system.

## Project Documentation
The project report and presentation are available in the `documentation/` directory, if included in the repository.
