# uva-spin/Temperature-Pressure-VIs

## LabVIEW Version

As of 2021-08-31.
The version of LabVIEW on the target computer at NM4 is "2019", "19.0.1f3", 64 bit.
Therefore you are recommended to *use version 2019 on your own computer* for development.

Only the latest version (2020 or 2021) is available when you install LabVIEW under the Evaluation license.
But you can install version 2019 from the NI package manager, once you activate the UVA license.

You could use the function of "Save for Previous Versions" when saving VI file in the latest version.
But it is not preferable since this function creates new VI file for the previous version and thus must be re-done every time.


## Device Communication Interface

| Device        | Type     | Gender | Wiring      | Screw | COM | IP4 |
| ------------- | -------- | ------ | ----------- | ----- | --- | --- |
| MKS 670       | Serial   | Male   | Straight    | Yes   | 13  |     |
| AMI 17000     | Serial   | Female | Straight(?) |       |     |     |
| THCD-400      | Serial   | Female | Straight(?) |       |     |     |
| DCU 600       | Ethernet | n/a    | n/a         |       |     |     |
| TPG-361       | Ethernet | n/a    | n/a         |       |     |     |
| LakeShore 218 | Serial   | Male   | Cross(?)    |       |     |     |
| MKS 946       | Serial   | Female | Straight    | Yes   | 13  |     |
