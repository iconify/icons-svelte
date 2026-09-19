<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="t1mfal-np"/><path class="ynx9m2bpq"/><path class="lnqxs73ma"/><path class="qzmyunh-t"/><path class="zdze1ib3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:discogs" {...props}></Icon>
<style>
:global(.cpk0fnbgt) {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.lnqxs73ma) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 7.5A16.5 16.5 0 0 0 7.5 24");
}

:global(.qzmyunh-t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 13a11 11 0 0 0-11 11m11 16.5A16.5 16.5 0 0 0 40.5 24");
}

:global(.t1mfal-np) {
  cx: 24px;
  cy: 24px;
  r: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ynx9m2bpq) {
  fill: currentColor;
  d: path("M24.75 24a.75.75 0 1 1-.75-.75a.76.76 0 0 1 .75.75");
}

:global(.zdze1ib3g) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 35a11 11 0 0 0 11-11");
}

</style>
