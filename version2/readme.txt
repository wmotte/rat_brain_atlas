mri.nii.gz          	T2-star weighted postmortem image, downscaled to 0.2mm isotropic.
mri_mask.nii.gz     	T2-star weighted postmortem image mask.

bssfp.nii.gz        	Average BSSFP invivo image (based on 80 rats; 4.7T scans), nonlinearly matched with 'mri.nii.gz'.
bssfp_mask.nii.gz   	Average BSSFP invivo image mask.

rois.nii.gz        	Waxholm atlas regions, bilateral (no discrimination between left/right).
rois.txt            	Waxholm atlas region labels.

rois_bilateral.nii.gz   Waxholm atlas regions, unilateral (discrimination between left/right).
rois_bilateral.txt      Waxholm atlas region, unilateral labels.

*** All images are scaled! 

So voxelsize in header is set to 2mm, rather than the 0.2mm (for registration purposes).
