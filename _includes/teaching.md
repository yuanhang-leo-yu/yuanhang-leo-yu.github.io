<h1 id="teaching"></h1>

<h2 style="margin: 0px 0px 10px;">
    Teaching
    <a href="#" class="btn btn-sm z-depth-0 custom-toggle-button" role="button" onclick="event.preventDefault(); toggleSection(this, 'teaching-content');">
        Expand
    </a>
</h2>

<div id="teaching-content" style="display:none;">
  <!-- Purdue University Section -->
  <h4 style="margin:0 10px 0;">Teaching Fellow, London School of Economics</h4>
  <ul style="margin:0 0 5px;">
    <li>Quantitative Approaches and Policy Analysis (2023 - 2026), Award: Krannert Certificate for Distinguished Teaching</li>
    <li>Introdutory Courses for Master of Public Administration (2023, 2024), Volunteer for Purdue Econ Assoc. (Undergrad Club)</li>
  </ul>

  <!-- Purdue TA Section -->
  <h4 style="margin:0 10px 0;">Teaching Assistant, London School of Economics</h4>
  <ul style="margin:0 0 5px;">
    <li>Econometrics I (2025), International Economics Summer School (2023), Introduction of Econometrics (2021 - 2022)</li>
  </ul>

  <!-- Yonsei University Section -->
 <!--  <h4 style="margin:0 10px 0;">Teaching Assistant, Yonsei University</h4>
  <ul style="margin:0 0 5px;">
    <li>Undergraduate: Labor Economics (Spring 2014-2016), Microeconomics (Spring 2015-2016)</li>
    <li>Graduate: Labor Economics (Spring 2014-2016)</li>
    <li>MBA: Personnel Economics (Fall 2015-Spring 2016), Microeconomics (Spring 2015-2016)</li>
  </ul> -->
</div>

<!-- JavaScript to toggle the section -->
<script>
  function toggleSection(button, contentId) {
    var content = document.getElementById(contentId);
    if (content.style.display === "none" || content.style.display === "") {
      content.style.display = "block";
      button.innerHTML = "Collapse";
    } else {
      content.style.display = "none";
      button.innerHTML = "Expand";
    }
  }
</script>

<!-- Optional CSS for button styling -->
<style>
  .custom-toggle-button {
    font-size: 12px;
    color: #000000;
    border: 0.5px solid #000000;
    padding-left: 0.25rem;
    padding-right: 0.25rem;
  }
</style>
