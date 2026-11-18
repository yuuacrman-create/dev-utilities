# dev-utilities
# Auto File Organizer CLI

A lightweight, zero-dependency Python utility that automatically scans and organizes cluttered directories by sorting files into categorized folders (Images, Documents, Code, Archives, Media).

## Features
- **Zero External Dependencies:** Built purely with Python's standard library (`os`, `shutil`, `pathlib`).
- **Customizable Categories:** Easily map new file extensions to custom directory names.
- **Safe Execution:** Automatically creates target folders and handles file-moving exceptions gracefully.

## Usage
Run the script inside any directory you want to clean up:

```bash
python file_organizer.py
