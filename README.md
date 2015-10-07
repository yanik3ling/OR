To run Danny’s code:

% include this folder and all subfolders on top of matlab’s search path
addpath(genpath(‘...\DannyReducedFolder’))
% run main function that reads .dcm files from folder and clusters with selected radius
[x1,x2,x3,x4,strips,fullstrips,stripinfo] = create3Dmodel('.dcm',0.0007)
% navigate to ‘...\DannyReducedFolder\Dataset 1’ and  click “select folder”
% enjoy the loading bar

