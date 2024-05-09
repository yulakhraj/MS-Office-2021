## MS-Office-2021
 
To install MS Office Follow these steps:
- Step 1: Download Office 2021 file from this repo.
- Step 2: Extract the file.
- Step 3: Run cmd as Administrator.
- Step 4: Go to file location office 2021.
- Step 5: Execute the given the command "setup/configure configuration.xml"


### For Activation
- *Run cmd as Administrator*
- Copy all below commands, **right click to paste into cmd window** at once then hit Enter.

```
if exist "C:\Program Files\Microsoft Office\Office16\ospp.vbs" cd /d "C:\Program Files\Microsoft Office\Office16"
if exist "C:\Program Files (x86)\Microsoft Office\Office16\ospp.vbs" cd /d "C:\Program Files (x86)\Microsoft Office\Office16"
for /f %x in ('dir /b ..\root\Licenses16\ProPlus2021VL_KMS*.xrm-ms') do cscript ospp.vbs /inslic:"..\root\Licenses16\%x"
cscript ospp.vbs /inpkey:FXYTK-NJJ8C-GB6DW-3DYQT-6F7TH
cscript ospp.vbs /sethst:kms.msgang.com
cscript ospp.vbs /act
pause
```
