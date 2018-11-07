twoDimension:
for every IP:
[time][feature];
time: 0-10s, 10-20s, 20-30s, 30-40s, 40-50s, 50-60s;
feature: numSrc, numDst, inFlow, outFlow, inBytes, outBytes, inPck, outPck, SrcDstRate flowRate, byteRate, pckRate, country

attackLog:
for every corresponding IP:
[time];
1-attack 0-no

threeDimension:
for every IP:
[time][feature][neighbors];
time: 0-10s, 10-20s, 20-30s, 30-40s, 40-50s, 50-60s; 
feature: inFlow, outFlow, inBytes, outBytes, inPck, outPck, SrcDstRate flowRate, byteRate, pckRate, country, neighborCountry, neighborIP; 
neighbor: the nodes that it talks to at that time slots

attackLog3:
for every corresponding IP:
[time][neighbors]; 
1-attack 0-no

statistics:
percentage of attack from edge level and node level; 
degree distribution
