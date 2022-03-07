*Das hier vorliegende Dokument ist für den internen Gebrauch geeignet. Etwaiger unsachgemäßer Gebrauch des Dokumentes beziehungsweise unautorisierte Weitergaben sind verboten und werden mit Disziplinarmaßnahmen getadelt.*

## Umfrage

<form name="contact" method="POST" data-netlify="true">
  <p>
    <label>Your Name: <input type="text" name="name" /></label>   
  </p>
  <p>
    <label>Your Email: <input type="email" name="email" /></label>
  </p>
  <p>
    <label>Your Role: <select name="role[]" multiple>
      <option value="leader">Leader</option>
      <option value="follower">Follower</option>
    </select></label>
  </p>
  <p>
    <label>Message: <textarea name="message"></textarea></label>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>