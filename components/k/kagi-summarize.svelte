<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="e9-xctb5h"/><path class="jm0ekozvd"/><circle class="f1b2facxd"/><path class="r0053gbsz"/><circle class="egxpq547j"/><path class="hr928kq0l"/><circle class="vbprgi39g"/><path class="jtrw3tc_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:kagi-summarize" {...props}></Icon>
<style>
:global(.e9-xctb5h) {
  width: 30.617px;
  height: 34.694px;
  x: 11.883px;
  y: 8.555px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.487px;
  ry: 5.487px;
}

:global(.egxpq547j) {
  cx: 19.095px;
  cy: 25.901px;
  r: 0.75px;
  fill: currentColor;
}

:global(.f1b2facxd) {
  cx: 19.095px;
  cy: 18.858px;
  r: 0.75px;
  fill: currentColor;
}

:global(.hr928kq0l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.552 25.901h13.746");
}

:global(.jm0ekozvd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.62 40.516h-1.633A5.486 5.486 0 0 1 5.5 35.028V10.24a5.486 5.486 0 0 1 5.487-5.487h19.645a5.46 5.46 0 0 1 5.213 3.8");
}

:global(.jtrw3tc_m) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.552 32.945h13.746");
}

:global(.r0053gbsz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.552 18.858h13.746");
}

:global(.vbprgi39g) {
  cx: 19.095px;
  cy: 32.945px;
  r: 0.75px;
  fill: currentColor;
}

</style>
