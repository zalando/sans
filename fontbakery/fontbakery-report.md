## FontBakery report

fontbakery version: 1.0.0







## Check results



<details><summary>[4] Family checks</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check that OS/2.fsSelection bold & italic settings are unique for each NameID1 <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-family-bold-italic-unique-for-nameid1">opentype/family/bold_italic_unique_for_nameid1</a></summary>
    <div>







* 🔥 **FAIL** <p>Family 'Zalando Sans' has 2 fonts (should be no more than 1) with the same OS/2.fsSelection bold &amp; italic settings: Bold=False, Italic=False</p>
 [code: unique-fsselection]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Verify that family names in the name table are consistent across all fonts in the family. Checks Typographic Family name (nameID 16) if present, otherwise uses Font Family name (nameID 1) <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-family-consistent-family-name">opentype/family/consistent_family_name</a></summary>
    <div>







* 🔥 **FAIL** <p>3 different Font Family names were found:</p>
<ul>
<li>
<p>'Zalando Sans' was found in:</p>
<ul>
<li>ZalandoSans[wdth,wght].ttf (nameID 1)</li>
<li>ZalandoSans[wdth,wght,slnt].ttf (nameID 1)</li>
<li>ZalandoSans-Italic[wdth,wght].ttf (nameID 1)</li>
</ul>
</li>
<li>
<p>'Zalando Sans Expanded' was found in:</p>
<ul>
<li>ZalandoSansExpanded[wght].ttf (nameID 1)</li>
<li>ZalandoSansExpanded-Italic[wght].ttf (nameID 1)</li>
</ul>
</li>
<li>
<p>'Zalando Sans Condensed' was found in:</p>
<ul>
<li>ZalandoSansCondensed[wght].ttf (nameID 1)</li>
<li>ZalandoSansCondensed-Italic[wght].ttf (nameID 1)</li>
</ul>
</li>
</ul>
 [code: inconsistent-family-name]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check that family axis ranges are indentical <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-varfont-family-axis-ranges">opentype/varfont/family_axis_ranges</a></summary>
    <div>







* 🔥 **FAIL** <p>Variable axes ranges not matching between font files</p>
 [code: axis-range-mismatch]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure that all variable font files have the same set of axes and axis ranges. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#varfont-consistent-axes">varfont/consistent_axes</a></summary>
    <div>







* 🔥 **FAIL** <p>ZalandoSans[wdth,wght].ttf: lacks a 'slnt' variation axis.</p>
 [code: missing-axis]



* 🔥 **FAIL** <p>ZalandoSansExpanded[wght].ttf: lacks a 'wdth' variation axis.</p>
 [code: missing-axis]



* 🔥 **FAIL** <p>ZalandoSansExpanded[wght].ttf: lacks a 'slnt' variation axis.</p>
 [code: missing-axis]



* 🔥 **FAIL** <p>ZalandoSansExpanded-Italic[wght].ttf: lacks a 'wdth' variation axis.</p>
 [code: missing-axis]



* 🔥 **FAIL** <p>ZalandoSansExpanded-Italic[wght].ttf: lacks a 'slnt' variation axis.</p>
 [code: missing-axis]



* 🔥 **FAIL** <p>ZalandoSansCondensed[wght].ttf: lacks a 'wdth' variation axis.</p>
 [code: missing-axis]



* 🔥 **FAIL** <p>ZalandoSansCondensed[wght].ttf: lacks a 'slnt' variation axis.</p>
 [code: missing-axis]



* 🔥 **FAIL** <p>ZalandoSans-Italic[wdth,wght].ttf: lacks a 'slnt' variation axis.</p>
 [code: missing-axis]



* 🔥 **FAIL** <p>ZalandoSansCondensed-Italic[wght].ttf: lacks a 'wdth' variation axis.</p>
 [code: missing-axis]



* 🔥 **FAIL** <p>ZalandoSansCondensed-Italic[wght].ttf: lacks a 'slnt' variation axis.</p>
 [code: missing-axis]



</div>
</details>
</div>
</details>

<details><summary>[17] ZalandoSans[wdth,wght,slnt].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Validates that all of the instance records in a given font have the same size. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-varfont-same-size-instance-records">opentype/varfont/same_size_instance_records</a></summary>
    <div>







* 🔥 **FAIL** <p>Instance records don't all have the same size.</p>
 [code: different-size-instance-records]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Validates subfamilyNameID and postScriptNameID for the default instance record <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-varfont-valid-default-instance-nameids">opentype/varfont/valid_default_instance_nameids</a></summary>
    <div>







* 🔥 **FAIL** <p>'Regular' instance has the same coordinates as the default instance; its postscript name should be 'ZalandoSans-Regular', instead of 'None'.</p>
 [code: invalid-default-instance-postscript-name]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Combined length of family and style must not exceed 32 characters. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#name-family-and-style-max-length">name/family_and_style_max_length</a></summary>
    <div>







* 🔥 **FAIL** <p>Variable font instance name 'Zalando Sans Condensed ExtraLight' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 272 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Zalando Sans Condensed ExtraLight Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 286 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Zalando Sans Condensed Light Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 288 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Zalando Sans Condensed Medium Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 292 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Zalando Sans Condensed SemiBold Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 294 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Zalando Sans Condensed Bold Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 296 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Zalando Sans Condensed ExtraBold Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 298 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Zalando Sans Expanded ExtraLight Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 314 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Zalando Sans Expanded Light Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 316 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Zalando Sans Expanded Medium Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 320 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Zalando Sans Expanded SemiBold Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 322 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Zalando Sans Expanded Bold Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 324 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Zalando Sans Expanded ExtraBold Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 326 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure smart dropout control is enabled in "prep" table instructions. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#smart-dropout">smart_dropout</a></summary>
    <div>







* 🔥 **FAIL** <p>The 'prep' table does not contain TrueType instructions enabling smart dropout control. To fix, export the font with autohinting enabled, or run ttfautohint on the font, or run the <code>gftools fix-nonhinting</code> script.</p>
 [code: lacks-smart-dropout]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check correctness of STAT table strings <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#STAT-strings">STAT_strings</a></summary>
    <div>







* 🔥 **FAIL** <p>The following AxisValue entries on the STAT table should not contain &quot;Italic&quot;:
['nameID 267: Italic']</p>
 [code: bad-italic]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking file is named canonically. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-canonical-filename">googlefonts/canonical_filename</a></summary>
    <div>







* 🔥 **FAIL** <p>Expected &quot;ZalandoSans[slnt,wdth,wght].ttf. Got ZalandoSans[wdth,wght,slnt].ttf.</p>
 [code: bad-filename]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check variable font instances <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-fvar-instances">googlefonts/fvar_instances</a></summary>
    <div>







* 🔥 **FAIL** <p>fvar instances are incorrect:</p>
<ul>
<li>Delete additional instances</li>
</ul>
<table>
<thead>
<tr>
<th align="left">Name</th>
<th align="left">current</th>
<th align="left">expected</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Condensed Light Italic</td>
<td align="left">wdth=75.0, wght=300.0, slnt=-10.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Condensed Bold Italic</td>
<td align="left">wdth=75.0, wght=700.0, slnt=-10.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Expanded SemiBold</td>
<td align="left">wdth=125.0, wght=600.0, slnt=0.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Condensed ExtraLight Italic</td>
<td align="left">wdth=75.0, wght=200.0, slnt=-10.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Expanded ExtraLight</td>
<td align="left">wdth=125.0, wght=200.0, slnt=0.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Condensed Medium Italic</td>
<td align="left">wdth=75.0, wght=500.0, slnt=-10.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Expanded SemiBold Italic</td>
<td align="left">wdth=125.0, wght=600.0, slnt=-10.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Expanded ExtraBold</td>
<td align="left">wdth=125.0, wght=800.0, slnt=0.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Expanded Bold</td>
<td align="left">wdth=125.0, wght=700.0, slnt=0.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Condensed ExtraLight</td>
<td align="left">wdth=75.0, wght=200.0, slnt=0.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Condensed Bold</td>
<td align="left">wdth=75.0, wght=700.0, slnt=0.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Condensed ExtraBold</td>
<td align="left">wdth=75.0, wght=800.0, slnt=0.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Condensed ExtraBold Italic</td>
<td align="left">wdth=75.0, wght=800.0, slnt=-10.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Condensed Italic</td>
<td align="left">wdth=75.0, wght=400.0, slnt=-10.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Expanded Light</td>
<td align="left">wdth=125.0, wght=300.0, slnt=0.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Condensed</td>
<td align="left">wdth=75.0, wght=400.0, slnt=0.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Condensed Light</td>
<td align="left">wdth=75.0, wght=300.0, slnt=0.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Expanded Medium</td>
<td align="left">wdth=125.0, wght=500.0, slnt=0.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Expanded Italic</td>
<td align="left">wdth=125.0, wght=400.0, slnt=-10.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Condensed Medium</td>
<td align="left">wdth=75.0, wght=500.0, slnt=0.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Expanded</td>
<td align="left">wdth=125.0, wght=400.0, slnt=0.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Expanded Bold Italic</td>
<td align="left">wdth=125.0, wght=700.0, slnt=-10.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Condensed SemiBold Italic</td>
<td align="left">wdth=75.0, wght=600.0, slnt=-10.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Expanded Medium Italic</td>
<td align="left">wdth=125.0, wght=500.0, slnt=-10.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Expanded ExtraBold Italic</td>
<td align="left">wdth=125.0, wght=800.0, slnt=-10.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Expanded Light Italic</td>
<td align="left">wdth=125.0, wght=300.0, slnt=-10.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Condensed SemiBold</td>
<td align="left">wdth=75.0, wght=600.0, slnt=0.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">Expanded ExtraLight Italic</td>
<td align="left">wdth=125.0, wght=200.0, slnt=-10.0</td>
<td align="left">N/A</td>
</tr>
<tr>
<td align="left">ExtraLight Italic</td>
<td align="left">wdth=100.0, wght=200.0, slnt=-10.0</td>
<td align="left">wdth=100.0, wght=200.0, slnt=-10.0</td>
</tr>
<tr>
<td align="left">ExtraLight</td>
<td align="left">wdth=100.0, wght=200.0, slnt=0.0</td>
<td align="left">wdth=100.0, wght=200.0, slnt=0.0</td>
</tr>
<tr>
<td align="left">Light Italic</td>
<td align="left">wdth=100.0, wght=300.0, slnt=-10.0</td>
<td align="left">wdth=100.0, wght=300.0, slnt=-10.0</td>
</tr>
<tr>
<td align="left">Light</td>
<td align="left">wdth=100.0, wght=300.0, slnt=0.0</td>
<td align="left">wdth=100.0, wght=300.0, slnt=0.0</td>
</tr>
<tr>
<td align="left">Italic</td>
<td align="left">wdth=100.0, wght=400.0, slnt=-10.0</td>
<td align="left">wdth=100.0, wght=400.0, slnt=-10.0</td>
</tr>
<tr>
<td align="left">Regular</td>
<td align="left">wdth=100.0, wght=400.0, slnt=0.0</td>
<td align="left">wdth=100.0, wght=400.0, slnt=0.0</td>
</tr>
<tr>
<td align="left">Medium Italic</td>
<td align="left">wdth=100.0, wght=500.0, slnt=-10.0</td>
<td align="left">wdth=100.0, wght=500.0, slnt=-10.0</td>
</tr>
<tr>
<td align="left">Medium</td>
<td align="left">wdth=100.0, wght=500.0, slnt=0.0</td>
<td align="left">wdth=100.0, wght=500.0, slnt=0.0</td>
</tr>
<tr>
<td align="left">SemiBold Italic</td>
<td align="left">wdth=100.0, wght=600.0, slnt=-10.0</td>
<td align="left">wdth=100.0, wght=600.0, slnt=-10.0</td>
</tr>
<tr>
<td align="left">SemiBold</td>
<td align="left">wdth=100.0, wght=600.0, slnt=0.0</td>
<td align="left">wdth=100.0, wght=600.0, slnt=0.0</td>
</tr>
<tr>
<td align="left">Bold Italic</td>
<td align="left">wdth=100.0, wght=700.0, slnt=-10.0</td>
<td align="left">wdth=100.0, wght=700.0, slnt=-10.0</td>
</tr>
<tr>
<td align="left">Bold</td>
<td align="left">wdth=100.0, wght=700.0, slnt=0.0</td>
<td align="left">wdth=100.0, wght=700.0, slnt=0.0</td>
</tr>
<tr>
<td align="left">ExtraBold Italic</td>
<td align="left">wdth=100.0, wght=800.0, slnt=-10.0</td>
<td align="left">wdth=100.0, wght=800.0, slnt=-10.0</td>
</tr>
<tr>
<td align="left">ExtraBold</td>
<td align="left">wdth=100.0, wght=800.0, slnt=0.0</td>
<td align="left">wdth=100.0, wght=800.0, slnt=0.0</td>
</tr>
</tbody>
</table>
 [code: bad-fvar-instances]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Is the Grid-fitting and Scan-conversion Procedure ('gasp') table set to optimize rendering? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-gasp">googlefonts/gasp</a></summary>
    <div>







* 🔥 **FAIL** <p>Font is missing the 'gasp' table. Try exporting the font with autohinting enabled.
If you are dealing with an unhinted font, it can be fixed by running the fonts through the command 'gftools fix-nonhinting'
GFTools is available at <a href="https://pypi.org/project/gftools/">https://pypi.org/project/gftools/</a></p>
 [code: lacks-gasp]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Validate STAT particle names and values match the fallback names in GFAxisRegistry. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-STAT-axisregistry">googlefonts/STAT/axisregistry</a></summary>
    <div>







* 🔥 **FAIL** <p>On the font variation axis 'slnt', the name 'Roman' is not among the expected ones (Default) according to the Google Fonts Axis Registry.</p>
 [code: invalid-name]



* 🔥 **FAIL** <p>On the font variation axis 'slnt', the name 'Italic' is not among the expected ones (Default) according to the Google Fonts Axis Registry.</p>
 [code: invalid-name]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Detect any interpolation issues in the font. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#interpolation-issues">interpolation_issues</a></summary>
    <div>







* ⚠️ **WARN** <p>Interpolation issues were found in the font:</p>
<pre><code>- Contour order differs in glyph 'numbersign': [0, 1, 2, 3] in wdth=100,wght=400,slnt=0, [1, 0, 2, 3] in wdth=100,wght=400,slnt=-10.

- Contour order differs in glyph 'numbersign': [0, 1, 2, 3] in wdth=100,wght=400,slnt=-10, [1, 0, 2, 3] in wdth=75,wght=400,slnt=0.

- Contour order differs in glyph 'numbersign': [0, 1, 2, 3] in wdth=100,wght=800,slnt=0, [1, 0, 2, 3] in wdth=75,wght=400,slnt=-10.

- Contour order differs in glyph 'numbersign': [0, 1, 2, 3] in wdth=100,wght=800,slnt=-10, [1, 0, 2, 3] in wdth=75,wght=200,slnt=0.

- Contour order differs in glyph 'numbersign': [0, 1, 2, 3] in wdth=125,wght=800,slnt=0, [1, 0, 2, 3] in wdth=75,wght=200,slnt=-10.

- Contour 0 start point differs in glyph 'exclamdown' between location wdth=100,wght=400,slnt=0 and location wdth=100,wght=400,slnt=-10

- Contour 0 in glyph 'exclamdown': becomes underweight between wdth=100,wght=400,slnt=0 and wdth=100,wght=400,slnt=-10.

- Contour 1 start point differs in glyph 'exclamdown' between location wdth=100,wght=400,slnt=0 and location wdth=100,wght=400,slnt=-10

- Contour 1 in glyph 'exclamdown': becomes underweight between wdth=100,wght=400,slnt=0 and wdth=100,wght=400,slnt=-10.

- Contour 0 start point differs in glyph 'exclamdown' between location wdth=100,wght=400,slnt=-10 and location wdth=75,wght=400,slnt=0

- Contour 0 in glyph 'exclamdown': becomes underweight between wdth=100,wght=400,slnt=-10 and wdth=75,wght=400,slnt=0.

- Contour 1 start point differs in glyph 'exclamdown' between location wdth=100,wght=400,slnt=-10 and location wdth=75,wght=400,slnt=0

- Contour 1 in glyph 'exclamdown': becomes underweight between wdth=100,wght=400,slnt=-10 and wdth=75,wght=400,slnt=0.

- Contour 0 start point differs in glyph 'exclamdown' between location wdth=100,wght=800,slnt=0 and location wdth=75,wght=400,slnt=-10

- Contour 0 in glyph 'exclamdown': becomes underweight between wdth=100,wght=800,slnt=0 and wdth=75,wght=400,slnt=-10.

- Contour 1 in glyph 'exclamdown': becomes underweight between wdth=100,wght=800,slnt=0 and wdth=75,wght=400,slnt=-10.

- Contour 0 start point differs in glyph 'exclamdown' between location wdth=100,wght=800,slnt=-10 and location wdth=75,wght=200,slnt=0

- Contour 0 in glyph 'exclamdown': becomes underweight between wdth=100,wght=800,slnt=-10 and wdth=75,wght=200,slnt=0.

- Contour 1 start point differs in glyph 'exclamdown' between location wdth=100,wght=800,slnt=-10 and location wdth=75,wght=200,slnt=0

- Contour 1 in glyph 'exclamdown': becomes underweight between wdth=100,wght=800,slnt=-10 and wdth=75,wght=200,slnt=0.

- Contour 0 start point differs in glyph 'exclamdown' between location wdth=125,wght=800,slnt=0 and location wdth=75,wght=200,slnt=-10

- Contour 0 in glyph 'exclamdown': becomes underweight between wdth=125,wght=800,slnt=0 and wdth=75,wght=200,slnt=-10.

- Contour 1 start point differs in glyph 'exclamdown' between location wdth=125,wght=800,slnt=0 and location wdth=75,wght=200,slnt=-10

- Contour 1 in glyph 'exclamdown': becomes underweight between wdth=125,wght=800,slnt=0 and wdth=75,wght=200,slnt=-10.

- Contour order differs in glyph 'guillemotleft': [0, 1] in wdth=100,wght=400,slnt=0, [1, 0] in wdth=100,wght=400,slnt=-10.

- Contour order differs in glyph 'guillemotleft': [0, 1] in wdth=100,wght=400,slnt=-10, [1, 0] in wdth=75,wght=400,slnt=0.

- Contour order differs in glyph 'guillemotleft': [0, 1] in wdth=100,wght=800,slnt=0, [1, 0] in wdth=75,wght=400,slnt=-10.

- Contour order differs in glyph 'guillemotleft': [0, 1] in wdth=100,wght=800,slnt=-10, [1, 0] in wdth=75,wght=200,slnt=0.

- Contour order differs in glyph 'guillemotleft': [0, 1] in wdth=125,wght=800,slnt=0, [1, 0] in wdth=75,wght=200,slnt=-10.

- Contour order differs in glyph 'guillemotright': [0, 1] in wdth=100,wght=400,slnt=0, [1, 0] in wdth=100,wght=400,slnt=-10.

- Contour order differs in glyph 'guillemotright': [0, 1] in wdth=100,wght=400,slnt=-10, [1, 0] in wdth=75,wght=400,slnt=0.

- Contour order differs in glyph 'guillemotright': [0, 1] in wdth=100,wght=800,slnt=0, [1, 0] in wdth=75,wght=400,slnt=-10.

- Contour order differs in glyph 'guillemotright': [0, 1] in wdth=100,wght=800,slnt=-10, [1, 0] in wdth=75,wght=200,slnt=0.

- Contour order differs in glyph 'guillemotright': [0, 1] in wdth=125,wght=800,slnt=0, [1, 0] in wdth=75,wght=200,slnt=-10.
</code></pre>
 [code: interpolation-issues]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#ligature-carets">ligature_carets</a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/variable does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, math, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: todhri, old-permic, math, hebrew, tai-le, syriac, tifinagh, canadian-aboriginal, coptic, duployan, malayalam</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition</li>
<li>U+0336 COMBINING LONG STROKE OVERLAY: not included in any glyphset definition</li>
<li>U+0337 COMBINING SHORT SOLIDUS OVERLAY: not included in any glyphset definition</li>
<li>U+0338 COMBINING LONG SOLIDUS OVERLAY: try adding math</li>
<li>U+2000 EN QUAD: try adding symbols2</li>
<li>U+2001 EM QUAD: try adding symbols2</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: try adding symbols2</li>
<li>U+2005 FOUR-PER-EM SPACE: try adding symbols2</li>
<li>U+2006 SIX-PER-EM SPACE: try adding symbols2</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: avestan, manichaean, siddham, sogdian, tirhuta, batak, hebrew, gunjala-gondi, brahmi, pahawh-hmong, warang-citi, zanabazar-square, tai-tham, bengali, hanifi-rohingya, mandaic, sharada, sundanese, lepcha, telugu, buhid, phags-pa, sinhala, khojki, lao, tagalog, syriac, tibetan, khmer, limbu, tifinagh, bhaiksuki, kaithi, modi, chakma, duployan, meetei-mayek, psalter-pahlavi, dogra, rejang, tamil, thai, khudawadi, nko, kayah-li, masaram-gondi, myanmar, javanese, grantha, syloti-nagri, mongolian, takri, arabic, malayalam, saurashtra, buginese, hanunoo, balinese, kharoshthi, newa, tagbanwa, tai-viet, new-tai-lue, tai-le, kannada, yi, oriya, gurmukhi, hatran, cham, gujarati, devanagari, thaana, mahajani</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: avestan, manichaean, siddham, sogdian, tirhuta, batak, hebrew, gunjala-gondi, brahmi, pahawh-hmong, warang-citi, zanabazar-square, tai-tham, bengali, hanifi-rohingya, mandaic, sharada, sundanese, lepcha, telugu, buhid, phags-pa, sinhala, khojki, lao, tagalog, syriac, tibetan, khmer, limbu, tifinagh, bhaiksuki, kaithi, modi, chakma, duployan, meetei-mayek, psalter-pahlavi, dogra, rejang, tamil, thai, khudawadi, nko, kayah-li, masaram-gondi, myanmar, javanese, grantha, syloti-nagri, old-hungarian, mongolian, takri, arabic, malayalam, saurashtra, buginese, hanunoo, balinese, kharoshthi, newa, tagbanwa, tai-viet, new-tai-lue, tai-le, kannada, yi, oriya, gurmukhi, cham, gujarati, devanagari, thaana, mahajani</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: nko, hebrew, syriac, arabic, thaana, phags-pa</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: nko, hebrew, syriac, thaana, phags-pa</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, yi, phags-pa</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2070 SUPERSCRIPT ZERO: try adding math</li>
<li>U+2074 SUPERSCRIPT FOUR: try adding math</li>
<li>U+2075 SUPERSCRIPT FIVE: try adding math</li>
<li>U+2076 SUPERSCRIPT SIX: try adding math</li>
<li>U+2077 SUPERSCRIPT SEVEN: try adding math</li>
<li>U+2078 SUPERSCRIPT EIGHT: try adding math</li>
<li>U+2079 SUPERSCRIPT NINE: try adding math</li>
<li>U+2080 SUBSCRIPT ZERO: try adding math</li>
<li>U+2081 SUBSCRIPT ONE: try adding math</li>
<li>U+2082 SUBSCRIPT TWO: try adding math</li>
<li>U+2083 SUBSCRIPT THREE: try adding math</li>
<li>U+2084 SUBSCRIPT FOUR: try adding math</li>
<li>U+2085 SUBSCRIPT FIVE: try adding math</li>
<li>U+2086 SUBSCRIPT SIX: try adding math</li>
<li>U+2087 SUBSCRIPT SEVEN: try adding math</li>
<li>U+2088 SUBSCRIPT EIGHT: try adding math</li>
<li>U+2089 SUBSCRIPT NINE: try adding math</li>
<li>U+2117 SOUND RECORDING COPYRIGHT: try adding math</li>
<li>U+2126 OHM SIGN: try adding math</li>
<li>U+2153 VULGAR FRACTION ONE THIRD: try adding symbols</li>
<li>U+2154 VULGAR FRACTION TWO THIRDS: try adding symbols</li>
<li>U+2190 LEFTWARDS ARROW: try adding one of: symbols, math</li>
<li>U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math</li>
<li>U+2196 NORTH WEST ARROW: try adding one of: symbols, math</li>
<li>U+2197 NORTH EAST ARROW: try adding one of: symbols, math</li>
<li>U+2198 SOUTH EAST ARROW: try adding one of: symbols, math</li>
<li>U+2199 SOUTH WEST ARROW: try adding one of: symbols, math</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+2205 EMPTY SET: try adding math</li>
<li>U+2206 INCREMENT: try adding math</li>
<li>U+220F N-ARY PRODUCT: try adding math</li>
<li>U+2211 N-ARY SUMMATION: try adding math</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CA LOZENGE: try adding one of: symbols, math</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: chinese-hongkong, yi, chinese-traditional, chinese-simplified, japanese, nushu, phags-pa</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* ⚠️ **WARN** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ſ</td>
<td align="left">de_Latn (German) and fr_Latn (French)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ʻ</td>
<td align="left">en_Latn (English)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ǥ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ʒ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ǯ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ǥ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ʒ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ǯ</td>
<td align="left">fi_Latn (Finnish)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to M when shaping the text 'M̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to m when shaping the text 'm̃'</td>
<td align="left">lt_Latn (Lithuanian)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ĳ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ĳ</td>
<td align="left">nl_Latn (Dutch)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#dotted-circle">dotted_circle</a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>

<details><summary>[7] ZalandoSans[wdth,wght].ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#ligature-carets">ligature_carets</a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/variable does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, math, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: todhri, old-permic, math, hebrew, tai-le, syriac, tifinagh, canadian-aboriginal, coptic, duployan, malayalam</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition</li>
<li>U+0336 COMBINING LONG STROKE OVERLAY: not included in any glyphset definition</li>
<li>U+0337 COMBINING SHORT SOLIDUS OVERLAY: not included in any glyphset definition</li>
<li>U+0338 COMBINING LONG SOLIDUS OVERLAY: try adding math</li>
<li>U+2000 EN QUAD: try adding symbols2</li>
<li>U+2001 EM QUAD: try adding symbols2</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: try adding symbols2</li>
<li>U+2005 FOUR-PER-EM SPACE: try adding symbols2</li>
<li>U+2006 SIX-PER-EM SPACE: try adding symbols2</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: avestan, manichaean, siddham, sogdian, tirhuta, batak, hebrew, gunjala-gondi, brahmi, pahawh-hmong, warang-citi, zanabazar-square, tai-tham, bengali, hanifi-rohingya, mandaic, sharada, sundanese, lepcha, telugu, buhid, phags-pa, sinhala, khojki, lao, tagalog, syriac, tibetan, khmer, limbu, tifinagh, bhaiksuki, kaithi, modi, chakma, duployan, meetei-mayek, psalter-pahlavi, dogra, rejang, tamil, thai, khudawadi, nko, kayah-li, masaram-gondi, myanmar, javanese, grantha, syloti-nagri, mongolian, takri, arabic, malayalam, saurashtra, buginese, hanunoo, balinese, kharoshthi, newa, tagbanwa, tai-viet, new-tai-lue, tai-le, kannada, yi, oriya, gurmukhi, hatran, cham, gujarati, devanagari, thaana, mahajani</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: avestan, manichaean, siddham, sogdian, tirhuta, batak, hebrew, gunjala-gondi, brahmi, pahawh-hmong, warang-citi, zanabazar-square, tai-tham, bengali, hanifi-rohingya, mandaic, sharada, sundanese, lepcha, telugu, buhid, phags-pa, sinhala, khojki, lao, tagalog, syriac, tibetan, khmer, limbu, tifinagh, bhaiksuki, kaithi, modi, chakma, duployan, meetei-mayek, psalter-pahlavi, dogra, rejang, tamil, thai, khudawadi, nko, kayah-li, masaram-gondi, myanmar, javanese, grantha, syloti-nagri, old-hungarian, mongolian, takri, arabic, malayalam, saurashtra, buginese, hanunoo, balinese, kharoshthi, newa, tagbanwa, tai-viet, new-tai-lue, tai-le, kannada, yi, oriya, gurmukhi, cham, gujarati, devanagari, thaana, mahajani</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: nko, hebrew, syriac, arabic, thaana, phags-pa</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: nko, hebrew, syriac, thaana, phags-pa</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, yi, phags-pa</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2070 SUPERSCRIPT ZERO: try adding math</li>
<li>U+2074 SUPERSCRIPT FOUR: try adding math</li>
<li>U+2075 SUPERSCRIPT FIVE: try adding math</li>
<li>U+2076 SUPERSCRIPT SIX: try adding math</li>
<li>U+2077 SUPERSCRIPT SEVEN: try adding math</li>
<li>U+2078 SUPERSCRIPT EIGHT: try adding math</li>
<li>U+2079 SUPERSCRIPT NINE: try adding math</li>
<li>U+2080 SUBSCRIPT ZERO: try adding math</li>
<li>U+2081 SUBSCRIPT ONE: try adding math</li>
<li>U+2082 SUBSCRIPT TWO: try adding math</li>
<li>U+2083 SUBSCRIPT THREE: try adding math</li>
<li>U+2084 SUBSCRIPT FOUR: try adding math</li>
<li>U+2085 SUBSCRIPT FIVE: try adding math</li>
<li>U+2086 SUBSCRIPT SIX: try adding math</li>
<li>U+2087 SUBSCRIPT SEVEN: try adding math</li>
<li>U+2088 SUBSCRIPT EIGHT: try adding math</li>
<li>U+2089 SUBSCRIPT NINE: try adding math</li>
<li>U+2117 SOUND RECORDING COPYRIGHT: try adding math</li>
<li>U+2126 OHM SIGN: try adding math</li>
<li>U+2153 VULGAR FRACTION ONE THIRD: try adding symbols</li>
<li>U+2154 VULGAR FRACTION TWO THIRDS: try adding symbols</li>
<li>U+2190 LEFTWARDS ARROW: try adding one of: symbols, math</li>
<li>U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math</li>
<li>U+2196 NORTH WEST ARROW: try adding one of: symbols, math</li>
<li>U+2197 NORTH EAST ARROW: try adding one of: symbols, math</li>
<li>U+2198 SOUTH EAST ARROW: try adding one of: symbols, math</li>
<li>U+2199 SOUTH WEST ARROW: try adding one of: symbols, math</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+2205 EMPTY SET: try adding math</li>
<li>U+2206 INCREMENT: try adding math</li>
<li>U+220F N-ARY PRODUCT: try adding math</li>
<li>U+2211 N-ARY SUMMATION: try adding math</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CA LOZENGE: try adding one of: symbols, math</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: chinese-hongkong, yi, chinese-traditional, chinese-simplified, japanese, nushu, phags-pa</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* ⚠️ **WARN** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ſ</td>
<td align="left">de_Latn (German) and fr_Latn (French)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ʻ</td>
<td align="left">en_Latn (English)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ǥ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ʒ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ǯ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ǥ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ʒ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ǯ</td>
<td align="left">fi_Latn (Finnish)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to M when shaping the text 'M̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to m when shaping the text 'm̃'</td>
<td align="left">lt_Latn (Lithuanian)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ĳ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ĳ</td>
<td align="left">nl_Latn (Dutch)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#dotted-circle">dotted_circle</a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>

<details><summary>[8] ZalandoSansExpanded[wght].ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#ligature-carets">ligature_carets</a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#unreachable-glyphs">unreachable_glyphs</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- Q.BRACKET.varAlt01

- cent.BRACKET.varAlt01

- dollar.BRACKET.varAlt01
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/variable does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, math, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: todhri, old-permic, math, hebrew, tai-le, syriac, tifinagh, canadian-aboriginal, coptic, duployan, malayalam</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition</li>
<li>U+0336 COMBINING LONG STROKE OVERLAY: not included in any glyphset definition</li>
<li>U+0337 COMBINING SHORT SOLIDUS OVERLAY: not included in any glyphset definition</li>
<li>U+0338 COMBINING LONG SOLIDUS OVERLAY: try adding math</li>
<li>U+2000 EN QUAD: try adding symbols2</li>
<li>U+2001 EM QUAD: try adding symbols2</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: try adding symbols2</li>
<li>U+2005 FOUR-PER-EM SPACE: try adding symbols2</li>
<li>U+2006 SIX-PER-EM SPACE: try adding symbols2</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: avestan, manichaean, siddham, sogdian, tirhuta, batak, hebrew, gunjala-gondi, brahmi, pahawh-hmong, warang-citi, zanabazar-square, tai-tham, bengali, hanifi-rohingya, mandaic, sharada, sundanese, lepcha, telugu, buhid, phags-pa, sinhala, khojki, lao, tagalog, syriac, tibetan, khmer, limbu, tifinagh, bhaiksuki, kaithi, modi, chakma, duployan, meetei-mayek, psalter-pahlavi, dogra, rejang, tamil, thai, khudawadi, nko, kayah-li, masaram-gondi, myanmar, javanese, grantha, syloti-nagri, mongolian, takri, arabic, malayalam, saurashtra, buginese, hanunoo, balinese, kharoshthi, newa, tagbanwa, tai-viet, new-tai-lue, tai-le, kannada, yi, oriya, gurmukhi, hatran, cham, gujarati, devanagari, thaana, mahajani</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: avestan, manichaean, siddham, sogdian, tirhuta, batak, hebrew, gunjala-gondi, brahmi, pahawh-hmong, warang-citi, zanabazar-square, tai-tham, bengali, hanifi-rohingya, mandaic, sharada, sundanese, lepcha, telugu, buhid, phags-pa, sinhala, khojki, lao, tagalog, syriac, tibetan, khmer, limbu, tifinagh, bhaiksuki, kaithi, modi, chakma, duployan, meetei-mayek, psalter-pahlavi, dogra, rejang, tamil, thai, khudawadi, nko, kayah-li, masaram-gondi, myanmar, javanese, grantha, syloti-nagri, old-hungarian, mongolian, takri, arabic, malayalam, saurashtra, buginese, hanunoo, balinese, kharoshthi, newa, tagbanwa, tai-viet, new-tai-lue, tai-le, kannada, yi, oriya, gurmukhi, cham, gujarati, devanagari, thaana, mahajani</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: nko, hebrew, syriac, arabic, thaana, phags-pa</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: nko, hebrew, syriac, thaana, phags-pa</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, yi, phags-pa</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2070 SUPERSCRIPT ZERO: try adding math</li>
<li>U+2074 SUPERSCRIPT FOUR: try adding math</li>
<li>U+2075 SUPERSCRIPT FIVE: try adding math</li>
<li>U+2076 SUPERSCRIPT SIX: try adding math</li>
<li>U+2077 SUPERSCRIPT SEVEN: try adding math</li>
<li>U+2078 SUPERSCRIPT EIGHT: try adding math</li>
<li>U+2079 SUPERSCRIPT NINE: try adding math</li>
<li>U+2080 SUBSCRIPT ZERO: try adding math</li>
<li>U+2081 SUBSCRIPT ONE: try adding math</li>
<li>U+2082 SUBSCRIPT TWO: try adding math</li>
<li>U+2083 SUBSCRIPT THREE: try adding math</li>
<li>U+2084 SUBSCRIPT FOUR: try adding math</li>
<li>U+2085 SUBSCRIPT FIVE: try adding math</li>
<li>U+2086 SUBSCRIPT SIX: try adding math</li>
<li>U+2087 SUBSCRIPT SEVEN: try adding math</li>
<li>U+2088 SUBSCRIPT EIGHT: try adding math</li>
<li>U+2089 SUBSCRIPT NINE: try adding math</li>
<li>U+2117 SOUND RECORDING COPYRIGHT: try adding math</li>
<li>U+2126 OHM SIGN: try adding math</li>
<li>U+2153 VULGAR FRACTION ONE THIRD: try adding symbols</li>
<li>U+2154 VULGAR FRACTION TWO THIRDS: try adding symbols</li>
<li>U+2190 LEFTWARDS ARROW: try adding one of: symbols, math</li>
<li>U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math</li>
<li>U+2196 NORTH WEST ARROW: try adding one of: symbols, math</li>
<li>U+2197 NORTH EAST ARROW: try adding one of: symbols, math</li>
<li>U+2198 SOUTH EAST ARROW: try adding one of: symbols, math</li>
<li>U+2199 SOUTH WEST ARROW: try adding one of: symbols, math</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+2205 EMPTY SET: try adding math</li>
<li>U+2206 INCREMENT: try adding math</li>
<li>U+220F N-ARY PRODUCT: try adding math</li>
<li>U+2211 N-ARY SUMMATION: try adding math</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CA LOZENGE: try adding one of: symbols, math</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: chinese-hongkong, yi, chinese-traditional, chinese-simplified, japanese, nushu, phags-pa</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* ⚠️ **WARN** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ſ</td>
<td align="left">de_Latn (German) and fr_Latn (French)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ʻ</td>
<td align="left">en_Latn (English)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ǥ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ʒ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ǯ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ǥ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ʒ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ǯ</td>
<td align="left">fi_Latn (Finnish)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to M when shaping the text 'M̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to m when shaping the text 'm̃'</td>
<td align="left">lt_Latn (Lithuanian)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ĳ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ĳ</td>
<td align="left">nl_Latn (Dutch)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#dotted-circle">dotted_circle</a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>

<details><summary>[9] ZalandoSansExpanded-Italic[wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Combined length of family and style must not exceed 32 characters. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#name-family-and-style-max-length">name/family_and_style_max_length</a></summary>
    <div>







* 🔥 **FAIL** <p>Variable font instance name 'Zalando Sans Expanded ExtraLight Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 336 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Zalando Sans Expanded Light Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 338 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Zalando Sans Expanded Medium Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 342 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Zalando Sans Expanded SemiBold Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 344 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Zalando Sans Expanded Bold Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 346 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Zalando Sans Expanded ExtraBold Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 348 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#ligature-carets">ligature_carets</a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#unreachable-glyphs">unreachable_glyphs</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- Q.BRACKET.varAlt01

- cent.BRACKET.varAlt01

- dollar.BRACKET.varAlt01
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/variable does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, math, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: todhri, old-permic, math, hebrew, tai-le, syriac, tifinagh, canadian-aboriginal, coptic, duployan, malayalam</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition</li>
<li>U+0336 COMBINING LONG STROKE OVERLAY: not included in any glyphset definition</li>
<li>U+0337 COMBINING SHORT SOLIDUS OVERLAY: not included in any glyphset definition</li>
<li>U+0338 COMBINING LONG SOLIDUS OVERLAY: try adding math</li>
<li>U+2000 EN QUAD: try adding symbols2</li>
<li>U+2001 EM QUAD: try adding symbols2</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: try adding symbols2</li>
<li>U+2005 FOUR-PER-EM SPACE: try adding symbols2</li>
<li>U+2006 SIX-PER-EM SPACE: try adding symbols2</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: avestan, manichaean, siddham, sogdian, tirhuta, batak, hebrew, gunjala-gondi, brahmi, pahawh-hmong, warang-citi, zanabazar-square, tai-tham, bengali, hanifi-rohingya, mandaic, sharada, sundanese, lepcha, telugu, buhid, phags-pa, sinhala, khojki, lao, tagalog, syriac, tibetan, khmer, limbu, tifinagh, bhaiksuki, kaithi, modi, chakma, duployan, meetei-mayek, psalter-pahlavi, dogra, rejang, tamil, thai, khudawadi, nko, kayah-li, masaram-gondi, myanmar, javanese, grantha, syloti-nagri, mongolian, takri, arabic, malayalam, saurashtra, buginese, hanunoo, balinese, kharoshthi, newa, tagbanwa, tai-viet, new-tai-lue, tai-le, kannada, yi, oriya, gurmukhi, hatran, cham, gujarati, devanagari, thaana, mahajani</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: avestan, manichaean, siddham, sogdian, tirhuta, batak, hebrew, gunjala-gondi, brahmi, pahawh-hmong, warang-citi, zanabazar-square, tai-tham, bengali, hanifi-rohingya, mandaic, sharada, sundanese, lepcha, telugu, buhid, phags-pa, sinhala, khojki, lao, tagalog, syriac, tibetan, khmer, limbu, tifinagh, bhaiksuki, kaithi, modi, chakma, duployan, meetei-mayek, psalter-pahlavi, dogra, rejang, tamil, thai, khudawadi, nko, kayah-li, masaram-gondi, myanmar, javanese, grantha, syloti-nagri, old-hungarian, mongolian, takri, arabic, malayalam, saurashtra, buginese, hanunoo, balinese, kharoshthi, newa, tagbanwa, tai-viet, new-tai-lue, tai-le, kannada, yi, oriya, gurmukhi, cham, gujarati, devanagari, thaana, mahajani</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: nko, hebrew, syriac, arabic, thaana, phags-pa</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: nko, hebrew, syriac, thaana, phags-pa</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, yi, phags-pa</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2070 SUPERSCRIPT ZERO: try adding math</li>
<li>U+2074 SUPERSCRIPT FOUR: try adding math</li>
<li>U+2075 SUPERSCRIPT FIVE: try adding math</li>
<li>U+2076 SUPERSCRIPT SIX: try adding math</li>
<li>U+2077 SUPERSCRIPT SEVEN: try adding math</li>
<li>U+2078 SUPERSCRIPT EIGHT: try adding math</li>
<li>U+2079 SUPERSCRIPT NINE: try adding math</li>
<li>U+2080 SUBSCRIPT ZERO: try adding math</li>
<li>U+2081 SUBSCRIPT ONE: try adding math</li>
<li>U+2082 SUBSCRIPT TWO: try adding math</li>
<li>U+2083 SUBSCRIPT THREE: try adding math</li>
<li>U+2084 SUBSCRIPT FOUR: try adding math</li>
<li>U+2085 SUBSCRIPT FIVE: try adding math</li>
<li>U+2086 SUBSCRIPT SIX: try adding math</li>
<li>U+2087 SUBSCRIPT SEVEN: try adding math</li>
<li>U+2088 SUBSCRIPT EIGHT: try adding math</li>
<li>U+2089 SUBSCRIPT NINE: try adding math</li>
<li>U+2117 SOUND RECORDING COPYRIGHT: try adding math</li>
<li>U+2126 OHM SIGN: try adding math</li>
<li>U+2153 VULGAR FRACTION ONE THIRD: try adding symbols</li>
<li>U+2154 VULGAR FRACTION TWO THIRDS: try adding symbols</li>
<li>U+2190 LEFTWARDS ARROW: try adding one of: symbols, math</li>
<li>U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math</li>
<li>U+2196 NORTH WEST ARROW: try adding one of: symbols, math</li>
<li>U+2197 NORTH EAST ARROW: try adding one of: symbols, math</li>
<li>U+2198 SOUTH EAST ARROW: try adding one of: symbols, math</li>
<li>U+2199 SOUTH WEST ARROW: try adding one of: symbols, math</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+2205 EMPTY SET: try adding math</li>
<li>U+2206 INCREMENT: try adding math</li>
<li>U+220F N-ARY PRODUCT: try adding math</li>
<li>U+2211 N-ARY SUMMATION: try adding math</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CA LOZENGE: try adding one of: symbols, math</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: chinese-hongkong, yi, chinese-traditional, chinese-simplified, japanese, nushu, phags-pa</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* ⚠️ **WARN** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ſ</td>
<td align="left">de_Latn (German) and fr_Latn (French)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ʻ</td>
<td align="left">en_Latn (English)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ǥ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ʒ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ǯ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ǥ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ʒ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ǯ</td>
<td align="left">fi_Latn (Finnish)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to M when shaping the text 'M̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to m when shaping the text 'm̃'</td>
<td align="left">lt_Latn (Lithuanian)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ĳ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ĳ</td>
<td align="left">nl_Latn (Dutch)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#dotted-circle">dotted_circle</a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>

<details><summary>[8] ZalandoSansCondensed[wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Combined length of family and style must not exceed 32 characters. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#name-family-and-style-max-length">name/family_and_style_max_length</a></summary>
    <div>







* 🔥 **FAIL** <p>Variable font instance name 'Zalando Sans Condensed ExtraLight' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 337 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* ⚠️ **WARN** <p>Name ID 6 'ZalandoSansCondensed-Regular' exceeds 27 characters. This has been found to cause problems with PostScript printers, especially on Mac platforms.</p>
 [code: nameid6-too-long]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#ligature-carets">ligature_carets</a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/variable does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, math, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: todhri, old-permic, math, hebrew, tai-le, syriac, tifinagh, canadian-aboriginal, coptic, duployan, malayalam</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition</li>
<li>U+0336 COMBINING LONG STROKE OVERLAY: not included in any glyphset definition</li>
<li>U+0337 COMBINING SHORT SOLIDUS OVERLAY: not included in any glyphset definition</li>
<li>U+0338 COMBINING LONG SOLIDUS OVERLAY: try adding math</li>
<li>U+2000 EN QUAD: try adding symbols2</li>
<li>U+2001 EM QUAD: try adding symbols2</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: try adding symbols2</li>
<li>U+2005 FOUR-PER-EM SPACE: try adding symbols2</li>
<li>U+2006 SIX-PER-EM SPACE: try adding symbols2</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: avestan, manichaean, siddham, sogdian, tirhuta, batak, hebrew, gunjala-gondi, brahmi, pahawh-hmong, warang-citi, zanabazar-square, tai-tham, bengali, hanifi-rohingya, mandaic, sharada, sundanese, lepcha, telugu, buhid, phags-pa, sinhala, khojki, lao, tagalog, syriac, tibetan, khmer, limbu, tifinagh, bhaiksuki, kaithi, modi, chakma, duployan, meetei-mayek, psalter-pahlavi, dogra, rejang, tamil, thai, khudawadi, nko, kayah-li, masaram-gondi, myanmar, javanese, grantha, syloti-nagri, mongolian, takri, arabic, malayalam, saurashtra, buginese, hanunoo, balinese, kharoshthi, newa, tagbanwa, tai-viet, new-tai-lue, tai-le, kannada, yi, oriya, gurmukhi, hatran, cham, gujarati, devanagari, thaana, mahajani</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: avestan, manichaean, siddham, sogdian, tirhuta, batak, hebrew, gunjala-gondi, brahmi, pahawh-hmong, warang-citi, zanabazar-square, tai-tham, bengali, hanifi-rohingya, mandaic, sharada, sundanese, lepcha, telugu, buhid, phags-pa, sinhala, khojki, lao, tagalog, syriac, tibetan, khmer, limbu, tifinagh, bhaiksuki, kaithi, modi, chakma, duployan, meetei-mayek, psalter-pahlavi, dogra, rejang, tamil, thai, khudawadi, nko, kayah-li, masaram-gondi, myanmar, javanese, grantha, syloti-nagri, old-hungarian, mongolian, takri, arabic, malayalam, saurashtra, buginese, hanunoo, balinese, kharoshthi, newa, tagbanwa, tai-viet, new-tai-lue, tai-le, kannada, yi, oriya, gurmukhi, cham, gujarati, devanagari, thaana, mahajani</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: nko, hebrew, syriac, arabic, thaana, phags-pa</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: nko, hebrew, syriac, thaana, phags-pa</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, yi, phags-pa</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2070 SUPERSCRIPT ZERO: try adding math</li>
<li>U+2074 SUPERSCRIPT FOUR: try adding math</li>
<li>U+2075 SUPERSCRIPT FIVE: try adding math</li>
<li>U+2076 SUPERSCRIPT SIX: try adding math</li>
<li>U+2077 SUPERSCRIPT SEVEN: try adding math</li>
<li>U+2078 SUPERSCRIPT EIGHT: try adding math</li>
<li>U+2079 SUPERSCRIPT NINE: try adding math</li>
<li>U+2080 SUBSCRIPT ZERO: try adding math</li>
<li>U+2081 SUBSCRIPT ONE: try adding math</li>
<li>U+2082 SUBSCRIPT TWO: try adding math</li>
<li>U+2083 SUBSCRIPT THREE: try adding math</li>
<li>U+2084 SUBSCRIPT FOUR: try adding math</li>
<li>U+2085 SUBSCRIPT FIVE: try adding math</li>
<li>U+2086 SUBSCRIPT SIX: try adding math</li>
<li>U+2087 SUBSCRIPT SEVEN: try adding math</li>
<li>U+2088 SUBSCRIPT EIGHT: try adding math</li>
<li>U+2089 SUBSCRIPT NINE: try adding math</li>
<li>U+2117 SOUND RECORDING COPYRIGHT: try adding math</li>
<li>U+2126 OHM SIGN: try adding math</li>
<li>U+2153 VULGAR FRACTION ONE THIRD: try adding symbols</li>
<li>U+2154 VULGAR FRACTION TWO THIRDS: try adding symbols</li>
<li>U+2190 LEFTWARDS ARROW: try adding one of: symbols, math</li>
<li>U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math</li>
<li>U+2196 NORTH WEST ARROW: try adding one of: symbols, math</li>
<li>U+2197 NORTH EAST ARROW: try adding one of: symbols, math</li>
<li>U+2198 SOUTH EAST ARROW: try adding one of: symbols, math</li>
<li>U+2199 SOUTH WEST ARROW: try adding one of: symbols, math</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+2205 EMPTY SET: try adding math</li>
<li>U+2206 INCREMENT: try adding math</li>
<li>U+220F N-ARY PRODUCT: try adding math</li>
<li>U+2211 N-ARY SUMMATION: try adding math</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CA LOZENGE: try adding one of: symbols, math</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: chinese-hongkong, yi, chinese-traditional, chinese-simplified, japanese, nushu, phags-pa</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* ⚠️ **WARN** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ſ</td>
<td align="left">de_Latn (German) and fr_Latn (French)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ʻ</td>
<td align="left">en_Latn (English)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ǥ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ʒ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ǯ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ǥ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ʒ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ǯ</td>
<td align="left">fi_Latn (Finnish)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to M when shaping the text 'M̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to m when shaping the text 'm̃'</td>
<td align="left">lt_Latn (Lithuanian)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ĳ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ĳ</td>
<td align="left">nl_Latn (Dutch)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#dotted-circle">dotted_circle</a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>

<details><summary>[7] ZalandoSans-Italic[wdth,wght].ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#ligature-carets">ligature_carets</a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/variable does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, math, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: todhri, old-permic, math, hebrew, tai-le, syriac, tifinagh, canadian-aboriginal, coptic, duployan, malayalam</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition</li>
<li>U+0336 COMBINING LONG STROKE OVERLAY: not included in any glyphset definition</li>
<li>U+0337 COMBINING SHORT SOLIDUS OVERLAY: not included in any glyphset definition</li>
<li>U+0338 COMBINING LONG SOLIDUS OVERLAY: try adding math</li>
<li>U+2000 EN QUAD: try adding symbols2</li>
<li>U+2001 EM QUAD: try adding symbols2</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: try adding symbols2</li>
<li>U+2005 FOUR-PER-EM SPACE: try adding symbols2</li>
<li>U+2006 SIX-PER-EM SPACE: try adding symbols2</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: avestan, manichaean, siddham, sogdian, tirhuta, batak, hebrew, gunjala-gondi, brahmi, pahawh-hmong, warang-citi, zanabazar-square, tai-tham, bengali, hanifi-rohingya, mandaic, sharada, sundanese, lepcha, telugu, buhid, phags-pa, sinhala, khojki, lao, tagalog, syriac, tibetan, khmer, limbu, tifinagh, bhaiksuki, kaithi, modi, chakma, duployan, meetei-mayek, psalter-pahlavi, dogra, rejang, tamil, thai, khudawadi, nko, kayah-li, masaram-gondi, myanmar, javanese, grantha, syloti-nagri, mongolian, takri, arabic, malayalam, saurashtra, buginese, hanunoo, balinese, kharoshthi, newa, tagbanwa, tai-viet, new-tai-lue, tai-le, kannada, yi, oriya, gurmukhi, hatran, cham, gujarati, devanagari, thaana, mahajani</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: avestan, manichaean, siddham, sogdian, tirhuta, batak, hebrew, gunjala-gondi, brahmi, pahawh-hmong, warang-citi, zanabazar-square, tai-tham, bengali, hanifi-rohingya, mandaic, sharada, sundanese, lepcha, telugu, buhid, phags-pa, sinhala, khojki, lao, tagalog, syriac, tibetan, khmer, limbu, tifinagh, bhaiksuki, kaithi, modi, chakma, duployan, meetei-mayek, psalter-pahlavi, dogra, rejang, tamil, thai, khudawadi, nko, kayah-li, masaram-gondi, myanmar, javanese, grantha, syloti-nagri, old-hungarian, mongolian, takri, arabic, malayalam, saurashtra, buginese, hanunoo, balinese, kharoshthi, newa, tagbanwa, tai-viet, new-tai-lue, tai-le, kannada, yi, oriya, gurmukhi, cham, gujarati, devanagari, thaana, mahajani</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: nko, hebrew, syriac, arabic, thaana, phags-pa</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: nko, hebrew, syriac, thaana, phags-pa</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, yi, phags-pa</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2070 SUPERSCRIPT ZERO: try adding math</li>
<li>U+2074 SUPERSCRIPT FOUR: try adding math</li>
<li>U+2075 SUPERSCRIPT FIVE: try adding math</li>
<li>U+2076 SUPERSCRIPT SIX: try adding math</li>
<li>U+2077 SUPERSCRIPT SEVEN: try adding math</li>
<li>U+2078 SUPERSCRIPT EIGHT: try adding math</li>
<li>U+2079 SUPERSCRIPT NINE: try adding math</li>
<li>U+2080 SUBSCRIPT ZERO: try adding math</li>
<li>U+2081 SUBSCRIPT ONE: try adding math</li>
<li>U+2082 SUBSCRIPT TWO: try adding math</li>
<li>U+2083 SUBSCRIPT THREE: try adding math</li>
<li>U+2084 SUBSCRIPT FOUR: try adding math</li>
<li>U+2085 SUBSCRIPT FIVE: try adding math</li>
<li>U+2086 SUBSCRIPT SIX: try adding math</li>
<li>U+2087 SUBSCRIPT SEVEN: try adding math</li>
<li>U+2088 SUBSCRIPT EIGHT: try adding math</li>
<li>U+2089 SUBSCRIPT NINE: try adding math</li>
<li>U+2117 SOUND RECORDING COPYRIGHT: try adding math</li>
<li>U+2126 OHM SIGN: try adding math</li>
<li>U+2153 VULGAR FRACTION ONE THIRD: try adding symbols</li>
<li>U+2154 VULGAR FRACTION TWO THIRDS: try adding symbols</li>
<li>U+2190 LEFTWARDS ARROW: try adding one of: symbols, math</li>
<li>U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math</li>
<li>U+2196 NORTH WEST ARROW: try adding one of: symbols, math</li>
<li>U+2197 NORTH EAST ARROW: try adding one of: symbols, math</li>
<li>U+2198 SOUTH EAST ARROW: try adding one of: symbols, math</li>
<li>U+2199 SOUTH WEST ARROW: try adding one of: symbols, math</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+2205 EMPTY SET: try adding math</li>
<li>U+2206 INCREMENT: try adding math</li>
<li>U+220F N-ARY PRODUCT: try adding math</li>
<li>U+2211 N-ARY SUMMATION: try adding math</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CA LOZENGE: try adding one of: symbols, math</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: chinese-hongkong, yi, chinese-traditional, chinese-simplified, japanese, nushu, phags-pa</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* ⚠️ **WARN** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ſ</td>
<td align="left">de_Latn (German) and fr_Latn (French)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ʻ</td>
<td align="left">en_Latn (English)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ǥ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ʒ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ǯ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ǥ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ʒ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ǯ</td>
<td align="left">fi_Latn (Finnish)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to M when shaping the text 'M̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to m when shaping the text 'm̃'</td>
<td align="left">lt_Latn (Lithuanian)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ĳ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ĳ</td>
<td align="left">nl_Latn (Dutch)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#dotted-circle">dotted_circle</a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>

<details><summary>[9] ZalandoSansCondensed-Italic[wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Combined length of family and style must not exceed 32 characters. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#name-family-and-style-max-length">name/family_and_style_max_length</a></summary>
    <div>







* 🔥 **FAIL** <p>Variable font instance name 'Zalando Sans Condensed ExtraLight Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 336 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Zalando Sans Condensed Light Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 338 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Zalando Sans Condensed Medium Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 342 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Zalando Sans Condensed SemiBold Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 344 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Zalando Sans Condensed Bold Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 346 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Zalando Sans Condensed ExtraBold Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 348 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#ligature-carets">ligature_carets</a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/variable does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, math, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: todhri, old-permic, math, hebrew, tai-le, syriac, tifinagh, canadian-aboriginal, coptic, duployan, malayalam</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition</li>
<li>U+0336 COMBINING LONG STROKE OVERLAY: not included in any glyphset definition</li>
<li>U+0337 COMBINING SHORT SOLIDUS OVERLAY: not included in any glyphset definition</li>
<li>U+0338 COMBINING LONG SOLIDUS OVERLAY: try adding math</li>
<li>U+2000 EN QUAD: try adding symbols2</li>
<li>U+2001 EM QUAD: try adding symbols2</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: try adding symbols2</li>
<li>U+2005 FOUR-PER-EM SPACE: try adding symbols2</li>
<li>U+2006 SIX-PER-EM SPACE: try adding symbols2</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: avestan, manichaean, siddham, sogdian, tirhuta, batak, hebrew, gunjala-gondi, brahmi, pahawh-hmong, warang-citi, zanabazar-square, tai-tham, bengali, hanifi-rohingya, mandaic, sharada, sundanese, lepcha, telugu, buhid, phags-pa, sinhala, khojki, lao, tagalog, syriac, tibetan, khmer, limbu, tifinagh, bhaiksuki, kaithi, modi, chakma, duployan, meetei-mayek, psalter-pahlavi, dogra, rejang, tamil, thai, khudawadi, nko, kayah-li, masaram-gondi, myanmar, javanese, grantha, syloti-nagri, mongolian, takri, arabic, malayalam, saurashtra, buginese, hanunoo, balinese, kharoshthi, newa, tagbanwa, tai-viet, new-tai-lue, tai-le, kannada, yi, oriya, gurmukhi, hatran, cham, gujarati, devanagari, thaana, mahajani</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: avestan, manichaean, siddham, sogdian, tirhuta, batak, hebrew, gunjala-gondi, brahmi, pahawh-hmong, warang-citi, zanabazar-square, tai-tham, bengali, hanifi-rohingya, mandaic, sharada, sundanese, lepcha, telugu, buhid, phags-pa, sinhala, khojki, lao, tagalog, syriac, tibetan, khmer, limbu, tifinagh, bhaiksuki, kaithi, modi, chakma, duployan, meetei-mayek, psalter-pahlavi, dogra, rejang, tamil, thai, khudawadi, nko, kayah-li, masaram-gondi, myanmar, javanese, grantha, syloti-nagri, old-hungarian, mongolian, takri, arabic, malayalam, saurashtra, buginese, hanunoo, balinese, kharoshthi, newa, tagbanwa, tai-viet, new-tai-lue, tai-le, kannada, yi, oriya, gurmukhi, cham, gujarati, devanagari, thaana, mahajani</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: nko, hebrew, syriac, arabic, thaana, phags-pa</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: nko, hebrew, syriac, thaana, phags-pa</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, yi, phags-pa</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2070 SUPERSCRIPT ZERO: try adding math</li>
<li>U+2074 SUPERSCRIPT FOUR: try adding math</li>
<li>U+2075 SUPERSCRIPT FIVE: try adding math</li>
<li>U+2076 SUPERSCRIPT SIX: try adding math</li>
<li>U+2077 SUPERSCRIPT SEVEN: try adding math</li>
<li>U+2078 SUPERSCRIPT EIGHT: try adding math</li>
<li>U+2079 SUPERSCRIPT NINE: try adding math</li>
<li>U+2080 SUBSCRIPT ZERO: try adding math</li>
<li>U+2081 SUBSCRIPT ONE: try adding math</li>
<li>U+2082 SUBSCRIPT TWO: try adding math</li>
<li>U+2083 SUBSCRIPT THREE: try adding math</li>
<li>U+2084 SUBSCRIPT FOUR: try adding math</li>
<li>U+2085 SUBSCRIPT FIVE: try adding math</li>
<li>U+2086 SUBSCRIPT SIX: try adding math</li>
<li>U+2087 SUBSCRIPT SEVEN: try adding math</li>
<li>U+2088 SUBSCRIPT EIGHT: try adding math</li>
<li>U+2089 SUBSCRIPT NINE: try adding math</li>
<li>U+2117 SOUND RECORDING COPYRIGHT: try adding math</li>
<li>U+2126 OHM SIGN: try adding math</li>
<li>U+2153 VULGAR FRACTION ONE THIRD: try adding symbols</li>
<li>U+2154 VULGAR FRACTION TWO THIRDS: try adding symbols</li>
<li>U+2190 LEFTWARDS ARROW: try adding one of: symbols, math</li>
<li>U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math</li>
<li>U+2196 NORTH WEST ARROW: try adding one of: symbols, math</li>
<li>U+2197 NORTH EAST ARROW: try adding one of: symbols, math</li>
<li>U+2198 SOUTH EAST ARROW: try adding one of: symbols, math</li>
<li>U+2199 SOUTH WEST ARROW: try adding one of: symbols, math</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+2205 EMPTY SET: try adding math</li>
<li>U+2206 INCREMENT: try adding math</li>
<li>U+220F N-ARY PRODUCT: try adding math</li>
<li>U+2211 N-ARY SUMMATION: try adding math</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CA LOZENGE: try adding one of: symbols, math</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: chinese-hongkong, yi, chinese-traditional, chinese-simplified, japanese, nushu, phags-pa</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* ⚠️ **WARN** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ſ</td>
<td align="left">de_Latn (German) and fr_Latn (French)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ʻ</td>
<td align="left">en_Latn (English)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ǥ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ʒ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ǯ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ǥ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ʒ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ǯ</td>
<td align="left">fi_Latn (Finnish)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to M when shaping the text 'M̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to m when shaping the text 'm̃'</td>
<td align="left">lt_Latn (Lithuanian)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ĳ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ĳ</td>
<td align="left">nl_Latn (Dutch)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#dotted-circle">dotted_circle</a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-alignment-miss">outline_alignment_miss</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* Aring (U+00C5): X=328.0,Y=713.0 (should be at cap-height 714?)

* Aring (U+00C5): X=328.0,Y=713.0 (should be at cap-height 714?)

* G (U+0047): X=287.0,Y=1.0 (should be at baseline 0?)

* Gbreve (U+011E): X=287.0,Y=1.0 (should be at baseline 0?)

* Gcircumflex (U+011C): X=287.0,Y=1.0 (should be at baseline 0?)

* uni0122 (U+0122): X=287.0,Y=1.0 (should be at baseline 0?)

* Gdotaccent (U+0120): X=287.0,Y=1.0 (should be at baseline 0?)

* OE (U+0152): X=419.0,Y=713.5 (should be at cap-height 714?)

* a (U+0061): X=343.0,Y=513.0 (should be at x-height 514?)

* a (U+0061): X=189.0,Y=-2.0 (should be at baseline 0?)

* aacute (U+00E1): X=189.0,Y=-2.0 (should be at baseline 0?)

* abreve (U+0103): X=189.0,Y=-2.0 (should be at baseline 0?)

* acircumflex (U+00E2): X=189.0,Y=-2.0 (should be at baseline 0?)

* adieresis (U+00E4): X=189.0,Y=-2.0 (should be at baseline 0?)

* agrave (U+00E0): X=189.0,Y=-2.0 (should be at baseline 0?)

* amacron (U+0101): X=189.0,Y=-2.0 (should be at baseline 0?)

* aogonek (U+0105): X=189.0,Y=-2.0 (should be at baseline 0?)

* aring (U+00E5): X=189.0,Y=-2.0 (should be at baseline 0?)

* atilde (U+00E3): X=189.0,Y=-2.0 (should be at baseline 0?)

* ae (U+00E6): X=199.0,Y=-1.5 (should be at baseline 0?)

* b (U+0062): X=181.5,Y=-1.5 (should be at baseline 0?)

* d (U+0064): X=311.0,Y=515.0 (should be at x-height 514?)

* eth (U+00F0): X=282.0,Y=715.0 (should be at cap-height 714?)

* eth (U+00F0): X=365.0,Y=712.0 (should be at cap-height 714?)

* g (U+0067): X=310.0,Y=515.0 (should be at x-height 514?)

* n (U+006E): X=386.5,Y=514.5 (should be at x-height 514?)

* p (U+0070): X=178.0,Y=-1.0 (should be at baseline 0?)

* thorn (U+00FE): X=180.0,Y=-1.0 (should be at baseline 0?)

* q (U+0071): X=309.0,Y=515.5 (should be at x-height 514?)

* s (U+0073): X=98.5,Y=-0.5 (should be at baseline 0?)

* s (U+0073): X=166.5,Y=514.5 (should be at x-height 514?)

* s (U+0073): X=246.5,Y=0.5 (should be at baseline 0?)

* sacute (U+015B): X=98.5,Y=-0.5 (should be at baseline 0?)

* sacute (U+015B): X=246.5,Y=0.5 (should be at baseline 0?)

* scaron (U+0161): X=98.5,Y=-0.5 (should be at baseline 0?)

* scaron (U+0161): X=246.5,Y=0.5 (should be at baseline 0?)

* scedilla (U+015F): X=98.5,Y=-0.5 (should be at baseline 0?)

* scedilla (U+015F): X=246.5,Y=0.5 (should be at baseline 0?)

* scircumflex (U+015D): X=98.5,Y=-0.5 (should be at baseline 0?)

* scircumflex (U+015D): X=246.5,Y=0.5 (should be at baseline 0?)

* uni0219 (U+0219): X=98.5,Y=-0.5 (should be at baseline 0?)

* uni0219 (U+0219): X=246.5,Y=0.5 (should be at baseline 0?)

* u (U+0075): X=95.0,Y=-0.5 (should be at baseline 0?)

* uacute (U+00FA): X=95.0,Y=-0.5 (should be at baseline 0?)

* ubreve (U+016D): X=95.0,Y=-0.5 (should be at baseline 0?)

* ucircumflex (U+00FB): X=95.0,Y=-0.5 (should be at baseline 0?)

* udieresis (U+00FC): X=95.0,Y=-0.5 (should be at baseline 0?)

* ugrave (U+00F9): X=95.0,Y=-0.5 (should be at baseline 0?)

* uhungarumlaut (U+0171): X=95.0,Y=-0.5 (should be at baseline 0?)

* umacron (U+016B): X=95.0,Y=-0.5 (should be at baseline 0?)

* uogonek (U+0173): X=95.0,Y=-0.5 (should be at baseline 0?)

* uring (U+016F): X=95.0,Y=-0.5 (should be at baseline 0?)

* three (U+0033): X=397.5,Y=715.5 (should be at cap-height 714?)

* five (U+0035): X=136.0,Y=2.0 (should be at baseline 0?)

* eight (U+0038): X=253.5,Y=712.0 (should be at cap-height 714?)

* three.ss02: X=397.5,Y=715.5 (should be at cap-height 714?)

* five.ss02: X=136.0,Y=2.0 (should be at baseline 0?)

* eight.ss02: X=253.5,Y=712.0 (should be at cap-height 714?)

* three.tf: X=417.5,Y=715.5 (should be at cap-height 714?)

* five.tf: X=151.0,Y=2.0 (should be at baseline 0?)

* eight.tf: X=258.5,Y=712.0 (should be at cap-height 714?)

* one.numr: X=193.0,Y=713.0 (should be at cap-height 714?)

* one.numr: X=251.0,Y=713.0 (should be at cap-height 714?)

* onehalf (U+00BD): X=193.0,Y=713.0 (should be at cap-height 714?)

* onehalf (U+00BD): X=251.0,Y=713.0 (should be at cap-height 714?)

* uni2153 (U+2153): X=193.0,Y=713.0 (should be at cap-height 714?)

* uni2153 (U+2153): X=251.0,Y=713.0 (should be at cap-height 714?)

* onequarter (U+00BC): X=193.0,Y=713.0 (should be at cap-height 714?)

* onequarter (U+00BC): X=251.0,Y=713.0 (should be at cap-height 714?)

* uni2080 (U+2080): X=308.0,Y=-1.0 (should be at baseline 0?)

* uni2080 (U+2080): X=166.0,Y=-0.5 (should be at baseline 0?)

* uni2070 (U+2070): X=284.5,Y=715.5 (should be at cap-height 714?)

* uni2070 (U+2070): X=205.0,Y=713.0 (should be at cap-height 714?)

* slash (U+002F): X=-6.0,Y=-2.0 (should be at baseline 0?)

* slash (U+002F): X=86.0,Y=-2.0 (should be at baseline 0?)

* slash (U+002F): X=-6.0,Y=-2.0 (should be at baseline 0?)

* backslash (U+005C): X=245.0,Y=-2.0 (should be at baseline 0?)

* backslash (U+005C): X=328.0,Y=-2.0 (should be at baseline 0?)

* backslash (U+005C): X=245.0,Y=-2.0 (should be at baseline 0?)

* ampersand (U+0026): X=137.5,Y=-0.5 (should be at baseline 0?)

* uni00B5 (U+00B5): X=134.5,Y=-2.0 (should be at baseline 0?)
</code></pre>
 [code: found-misalignments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 16 | 53 | 595 | 42 | 844 | 0 | 
| 0% | 0% | 1% | 3% | 38% | 3% | 54% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
