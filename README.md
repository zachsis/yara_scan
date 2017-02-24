# yara_scan
Python Yara scanner to scan files with all your rules from a folder and ignore invalid rules

Script allows you to specify a folder full of yara rules and scan a folder with all the rules.  It will also still work if some of the rules are invalid and just print out the invalid rules so you can fix them later.

usage: 
python yara_scan.py -y <yara_rule_dir> [-s <scan_files_dir> (optional otherwise current dir is scanned)]


