https://en.wikipedia.org/wiki/List_of_XML_and_HTML_character_entity_references
&#955;
&#9675;
&#8226;
&#8728;
&#8593;
&#8595;
&#177;

123<sub>(&#177;456)</sub>
123<sub><sup>(&#177;456)</sup></sub>
123<sup><sub>(&#177;456)</sub></sup>

123<small>(&#177;456)</small>

# iESBM Benchmark
Last update: 2020-04-19

iESBM, an interpretative Entity Summarization Benchmark on Multiple Datasets.

# Results

## FER Results

<strong>Table 1. FER on each dataset for k=5.</strong>
<table class="tablesorter" id="tb_fer_top5">
<thead>
<tr><th data-sorter="false" class="header"></th><th class="header">LFoP</th>
<th class="header">GFoP</th>
<th class="header">GFoV</th>
<th class="header">IoPV</th>
<th class="header">DoP</th>
<th class="header">DoV</th>
</tr>
</thead>
<tbody>
<tr>
<td>ESBM-D</td><td>0.721</td><td>0.915</td><td>0.774</td><td>1.295</td><td>2.478</td><td>1.016</td></tr>
<tr>
<td>ESBM-L</td><td>0.581</td><td>0.998</td><td>1.349</td><td>0.864</td><td>3.093</td><td>1.061</td></tr>
<tr>
<td>FED</td><td>0.821</td><td>1.012</td><td>1.148</td><td>0.958</td><td>1.699</td><td>1.016</td></tr>
</tbody></table>

<strong>Table 2. FER on each dataset for k=10.</strong>
<table class="tablesorter" id="tb_fer_top10">
<thead>
<tr><th data-sorter="false" class="header"></th><th class="header">LFoP</th>
<th class="header">GFoP</th>
<th class="header">GFoV</th>
<th class="header">IoPV</th>
<th class="header">DoP</th>
<th class="header">DoV</th>
</tr>
</thead>
<tbody>
<tr>
<td>ESBM-D</td><td>0.742</td><td>0.906</td><td>0.772</td><td>1.291</td><td>2.080</td><td>1.002</td></tr>
<tr>
<td>ESBM-L</td><td>0.757</td><td>0.983</td><td>1.203</td><td>0.917</td><td>2.092</td><td>1.047</td></tr>
<tr>
<td>FED</td><td>0.862</td><td>0.993</td><td>1.065</td><td>0.981</td><td>1.601</td><td>1.018</td></tr>
</tbody></table>


## FSR Results
FSR results for several selected entity summarizers are presented in the following tables. Their output files are also available (outs_eval).

<strong>Table 3. FSR of selected entity summarizers on ESBM-D for k=5.</strong>

<table class="tablesorter" id="tb_fsr_dbpedia_top5">
<thead>
<tr><th data-sorter="false" class="header"></th><th class="header">LFoP</th>
<th class="header">GFoP</th>
<th class="header">GFoV</th>
<th class="header">IoPV</th>
<th class="header">DoP</th>
<th class="header">DoV</th>
</tr>
</thead>
<tbody>
<tr>
<td>FER</td><td>0.721</td><td>0.915</td><td>0.774</td><td>1.295</td><td>2.478</td><td>1.016</td></tr>
<tr>
<td>RELIN</td><td>0.280</td><td>0.869</td><td>0.277</td><td>1.801</td><td>2.351</td><td>0.749</td></tr>
<tr>
<td>DIVERSUM</td><td>0.649</td><td>0.910</td><td>0.854</td><td>1.175</td><td>2.753</td><td>1.037</td></tr>
<tr>
<td>FACES</td><td>0.322</td><td>0.849</td><td>0.805</td><td>1.231</td><td>2.664</td><td>0.987</td></tr>
<tr>
<td>FACES-E</td><td>0.623</td><td>0.914</td><td>0.911</td><td>1.142</td><td>2.494</td><td>0.972</td></tr>
<tr>
<td>CD</td><td>0.334</td><td>0.863</td><td>0.414</td><td>1.620</td><td>2.742</td><td>1.061</td></tr>
<tr>
<td>LinkSUM</td><td>0.350</td><td>0.839</td><td>0.901</td><td>1.147</td><td>1.913</td><td>0.976</td></tr>
<tr>
<td>BAFREC</td><td>0.585</td><td>0.954</td><td>0.908</td><td>1.117</td><td>2.586</td><td>0.980</td></tr>
<tr>
<td>KAFCA</td><td>0.361</td><td>0.850</td><td>0.646</td><td>1.377</td><td>2.505</td><td>0.993</td></tr>
<tr>
<td>MPSUM</td><td>0.434</td><td>0.876</td><td>0.730</td><td>1.304</td><td>2.742</td><td>0.891</td></tr>
<tr>
<td>ESA</td><td>0.266</td><td>0.848</td><td>0.529</td><td>1.535</td><td>2.303</td><td>0.930</td></tr>
<tr>
<td>DeepLENS</td><td>0.302</td><td>0.854</td><td>0.656</td><td>1.407</td><td>2.415</td><td>0.957</td></tr>
</tbody></table>

<strong>Table 4. FSR of selected entity summarizers on ESBM-L for k=5.</strong>
%table: (<TOPK.top5: 5>, 'lmdb')
<table class="tablesorter" id="tb_fsr_lmdb_top5">
<thead>
<tr><th data-sorter="false" class="header"></th><th class="header">LFoP</th>
<th class="header">GFoP</th>
<th class="header">GFoV</th>
<th class="header">IoPV</th>
<th class="header">DoP</th>
<th class="header">DoV</th>
</tr>
</thead>
<tbody>
<tr>
<td>FER</td>
<td>0.581</td><td>0.998</td><td>1.349</td><td>0.864</td><td>3.093</td><td>1.061</td></tr>
<tr>
<td>RELIN</td>
<td>0.688</td><td>0.991</td><td>0.600</td><td>1.154</td><td>2.775</td><td>0.966</td></tr>
<tr>
<td>DIVERSUM</td>
<td>0.870</td><td>0.993</td><td>1.006</td><td>0.991</td><td>3.869</td><td>1.091</td></tr>
<tr>
<td>FACES</td>
<td>0.728</td><td>0.953</td><td>1.128</td><td>0.947</td><td>3.869</td><td>1.065</td></tr>
<tr>
<td>FACES-E</td>
<td>0.536</td><td>0.962</td><td>1.341</td><td>0.872</td><td>3.848</td><td>1.058</td></tr>
<tr>
<td>CD</td>
<td>0.470</td><td>0.996</td><td>1.009</td><td>0.959</td><td>3.869</td><td>1.102</td></tr>
<tr>
<td>LinkSUM</td>
<td>1.026</td><td>0.958</td><td>1.288</td><td>0.894</td><td>1.510</td><td>0.974</td></tr>
<tr>
<td>BAFREC</td>
<td>0.562</td><td>1.020</td><td>1.598</td><td>0.781</td><td>3.485</td><td>1.009</td></tr>
<tr>
<td>KAFCA</td>
<td>0.234</td><td>0.954</td><td>1.309</td><td>0.884</td><td>3.869</td><td>1.101</td></tr>
<tr>
<td>MPSUM</td>
<td>0.568</td><td>0.979</td><td>1.249</td><td>0.908</td><td>3.869</td><td>1.082</td></tr>
<tr>
<td>ESA</td>
<td>0.514</td><td>1.029</td><td>1.241</td><td>0.892</td><td>3.125</td><td>1.013</td></tr>
<tr>
<td>DeepLENS</td>
<td>0.361</td><td>1.004</td><td>1.412</td><td>0.840</td><td>3.496</td><td>1.001</td></tr>
</tbody></table>

<strong>Table 5. FSR of selected entity summarizers on FED for k=5.</strong>
<table class="tablesorter" id="tb_fsr_dsfaces_top5">
<thead>
<tr><th data-sorter="false" class="header"></th><th class="header">LFoP</th>
<th class="header">GFoP</th>
<th class="header">GFoV</th>
<th class="header">IoPV</th>
<th class="header">DoP</th>
<th class="header">DoV</th>
</tr>
</thead>
<tbody>
<tr>
<td>FER</td>
<td>0.821</td><td>1.012</td><td>1.148</td><td>0.958</td><td>1.699</td><td>1.016</td></tr>
<tr>
<td>RELIN</td>
<td>0.911</td><td>1.028</td><td>0.652</td><td>1.123</td><td>1.473</td><td>0.761</td></tr>
<tr>
<td>DIVERSUM</td>
<td>1.339</td><td>0.962</td><td>1.043</td><td>0.989</td><td>1.783</td><td>0.981</td></tr>
<tr>
<td>FACES</td>
<td>0.860</td><td>0.936</td><td>1.489</td><td>0.886</td><td>1.714</td><td>1.019</td></tr>
<tr>
<td>FACES-E</td>
<td>0.860</td><td>0.936</td><td>1.489</td><td>0.886</td><td>1.714</td><td>1.019</td></tr>
<tr>
<td>CD</td>
<td>0.799</td><td>1.042</td><td>0.699</td><td>1.118</td><td>1.783</td><td>1.060</td></tr>
<tr>
<td>LinkSUM</td>
<td>0.976</td><td>0.987</td><td>1.656</td><td>0.797</td><td>1.460</td><td>1.062</td></tr>
<tr>
<td>BAFREC</td>
<td>0.928</td><td>0.949</td><td>1.658</td><td>0.811</td><td>1.768</td><td>0.975</td></tr>
<tr>
<td>KAFCA</td>
<td>0.636</td><td>0.999</td><td>0.864</td><td>1.024</td><td>1.699</td><td>0.909</td></tr>
<tr>
<td>MPSUM</td>
<td>0.878</td><td>0.918</td><td>1.344</td><td>0.949</td><td>1.783</td><td>0.821</td></tr>
<tr>
<td>ESA</td>
<td>0.842</td><td>1.090</td><td>0.813</td><td>1.039</td><td>1.378</td><td>0.875</td></tr>
<tr>
<td>DeepLENS</td>
<td>0.823</td><td>1.056</td><td>1.166</td><td>0.926</td><td>1.481</td><td>0.863</td></tr>
</tbody></table>

<strong>Table 6. FSR of selected entity summarizers on ESBM-D for k=10.</strong>
<table class="tablesorter" id="tb_fsr_dbpedia_top10">
<thead>
<tr><th data-sorter="false" class="header"></th><th class="header">LFoP</th>
<th class="header">GFoP</th>
<th class="header">GFoV</th>
<th class="header">IoPV</th>
<th class="header">DoP</th>
<th class="header">DoV</th>
</tr>
</thead>
<tbody>
<tr>
<td>FER</td>
<td>0.742</td><td>0.906</td><td>0.772</td><td>1.291</td><td>2.080</td><td>1.002</td></tr>
<tr>
<td>RELIN</td>
<td>0.392</td><td>0.879</td><td>0.374</td><td>1.655</td><td>2.015</td><td>0.872</td></tr>
<tr>
<td>DIVERSUM</td>
<td>0.413</td><td>0.861</td><td>0.745</td><td>1.299</td><td>2.753</td><td>1.013</td></tr>
<tr>
<td>FACES</td>
<td>0.301</td><td>0.840</td><td>0.742</td><td>1.299</td><td>2.658</td><td>0.968</td></tr>
<tr>
<td>FACES-E</td>
<td>0.516</td><td>0.897</td><td>0.770</td><td>1.270</td><td>2.453</td><td>0.985</td></tr>
<tr>
<td>CD</td>
<td>0.393</td><td>0.871</td><td>0.555</td><td>1.467</td><td>2.538</td><td>1.026</td></tr>
<tr>
<td>LinkSUM</td>
<td>0.438</td><td>0.889</td><td>0.751</td><td>1.267</td><td>1.580</td><td>0.937</td></tr>
<tr>
<td>BAFREC</td>
<td>0.629</td><td>0.945</td><td>0.850</td><td>1.171</td><td>1.926</td><td>0.968</td></tr>
<tr>
<td>KAFCA</td>
<td>0.443</td><td>0.883</td><td>0.661</td><td>1.359</td><td>2.199</td><td>0.972</td></tr>
<tr>
<td>MPSUM</td>
<td>0.405</td><td>0.880</td><td>0.686</td><td>1.349</td><td>2.612</td><td>0.971</td></tr>
<tr>
<td>ESA</td>
<td>0.309</td><td>0.839</td><td>0.606</td><td>1.442</td><td>2.088</td><td>0.965</td></tr>
<tr>
<td>DeepLENS</td>
<td>0.334</td><td>0.827</td><td>0.674</td><td>1.367</td><td>2.070</td><td>0.994</td></tr>
</tbody></table>

<strong>Table 7. FSR of selected entity summarizers on ESBM-L for k=10.</strong>
<table class="tablesorter" id="tb_fsr_lmdb_top10">
<thead>
<tr><th data-sorter="false" class="header"></th><th class="header">LFoP</th>
<th class="header">GFoP</th>
<th class="header">GFoV</th>
<th class="header">IoPV</th>
<th class="header">DoP</th>
<th class="header">DoV</th>
</tr>
</thead>
<tbody>
<tr>
<td>FER</td>
<td>0.757</td><td>0.983</td><td>1.203</td><td>0.917</td><td>2.092</td><td>1.047</td></tr>
<tr>
<td>RELIN</td>
<td>0.865</td><td>1.000</td><td>0.634</td><td>1.143</td><td>1.962</td><td>0.950</td></tr>
<tr>
<td>DIVERSUM</td>
<td>0.570</td><td>0.965</td><td>1.221</td><td>0.922</td><td>3.869</td><td>1.083</td></tr>
<tr>
<td>FACES</td>
<td>0.730</td><td>0.962</td><td>0.976</td><td>0.994</td><td>3.869</td><td>1.057</td></tr>
<tr>
<td>FACES-E</td>
<td>0.470</td><td>0.953</td><td>1.398</td><td>0.867</td><td>3.856</td><td>1.056</td></tr>
<tr>
<td>CD</td>
<td>0.560</td><td>0.992</td><td>1.302</td><td>0.885</td><td>2.904</td><td>1.079</td></tr>
<tr>
<td>LinkSUM</td>
<td>1.127</td><td>0.981</td><td>1.042</td><td>0.979</td><td>1.055</td><td>0.889</td></tr>
<tr>
<td>BAFREC</td>
<td>0.714</td><td>1.005</td><td>1.360</td><td>0.861</td><td>2.235</td><td>0.943</td></tr>
<tr>
<td>KAFCA</td>
<td>0.407</td><td>0.969</td><td>1.336</td><td>0.874</td><td>3.119</td><td>1.069</td></tr>
<tr>
<td>MPSUM</td>
<td>0.564</td><td>0.977</td><td>1.261</td><td>0.909</td><td>3.428</td><td>1.078</td></tr>
<tr>
<td>ESA</td>
<td>0.662</td><td>0.993</td><td>1.187</td><td>0.919</td><td>2.257</td><td>1.022</td></tr>
<tr>
<td>DeepLENS</td>
<td>0.643</td><td>0.974</td><td>1.210</td><td>0.910</td><td>2.284</td><td>1.061</td></tr>
</tbody></table>

<strong>Table 8. FSR of selected entity summarizers on FED for k=10.</strong>
<table class="tablesorter" id="tb_fsr_dsfaces_top10">
<thead>
<tr><th data-sorter="false" class="header"></th><th class="header">LFoP</th>
<th class="header">GFoP</th>
<th class="header">GFoV</th>
<th class="header">IoPV</th>
<th class="header">DoP</th>
<th class="header">DoV</th>
</tr>
</thead>
<tbody>
<tr>
<td>FER</td>
<td>0.862</td><td>0.993</td><td>1.065</td><td>0.981</td><td>1.601</td><td>1.018</td></tr>
<tr>
<td>RELIN</td>
<td>0.883</td><td>1.042</td><td>0.545</td><td>1.151</td><td>1.495</td><td>0.889</td></tr>
<tr>
<td>DIVERSUM</td>
<td>1.021</td><td>0.943</td><td>1.115</td><td>0.978</td><td>1.783</td><td>1.011</td></tr>
<tr>
<td>FACES</td>
<td>0.905</td><td>0.928</td><td>1.315</td><td>0.933</td><td>1.584</td><td>1.012</td></tr>
<tr>
<td>FACES-E</td>
<td>0.905</td><td>0.928</td><td>1.315</td><td>0.933</td><td>1.584</td><td>1.012</td></tr>
<tr>
<td>CD</td>
<td>0.735</td><td>1.022</td><td>0.840</td><td>1.050</td><td>1.783</td><td>1.055</td></tr>
<tr>
<td>LinkSUM</td>
<td>1.028</td><td>0.964</td><td>1.366</td><td>0.893</td><td>1.301</td><td>1.052</td></tr>
<tr>
<td>BAFREC</td>
<td>0.870</td><td>0.926</td><td>1.433</td><td>0.890</td><td>1.634</td><td>0.998</td></tr>
<tr>
<td>KAFCA</td>
<td>0.680</td><td>0.984</td><td>0.972</td><td>0.996</td><td>1.624</td><td>0.975</td></tr>
<tr>
<td>MPSUM</td>
<td>0.804</td><td>0.909</td><td>1.256</td><td>0.954</td><td>1.783</td><td>0.958</td></tr>
<tr>
<td>ESA</td>
<td>0.832</td><td>1.047</td><td>0.896</td><td>1.020</td><td>1.292</td><td>0.926</td></tr>
<tr>
<td>DeepLENS</td>
<td>0.863</td><td>0.999</td><td>1.116</td><td>0.955</td><td>1.334</td><td>0.908</td></tr>
</tbody></table>








