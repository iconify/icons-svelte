<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="pgc60gb8f"/><path class="x4-j7eg3k"/><path class="bjcf95bza"/><circle class="bs7tzob_p"/><circle class="rixy4-bfm"/><circle class="hnbupob0l"/><circle class="y2ugsl6kt"/><circle class="crsll0bvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:linwood" {...props}></Icon>
<style>
:global(.bjcf95bza) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.066 28.992v3.441a9.176 9.176 0 0 1-9.176 9.176H17.067a9.176 9.176 0 0 1-9.176-9.176v-3.44");
}

:global(.bs7tzob_p) {
  cx: 37.841px;
  cy: 12.078px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.crsll0bvn) {
  cx: 36.701px;
  cy: 24.691px;
  r: 0.75px;
  fill: currentColor;
}

:global(.hnbupob0l) {
  cx: 10.16px;
  cy: 12.078px;
  r: 0.75px;
  fill: currentColor;
}

:global(.pgc60gb8f) {
  cx: 10.16px;
  cy: 12.078px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.rixy4-bfm) {
  cx: 37.841px;
  cy: 12.078px;
  r: 0.75px;
  fill: currentColor;
}

:global(.x4-j7eg3k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.979 38.168h6.912a9.176 9.176 0 0 0 9.175-9.176h0v-5.867a9.12 9.12 0 0 0-1.76-5.39a5.682 5.682 0 1 0-5.771-3.631a9 9 0 0 0-1.644-.155H17.067a9 9 0 0 0-1.644.155a5.655 5.655 0 1 0-5.771 3.632a9.12 9.12 0 0 0-1.76 5.389v5.867a9.176 9.176 0 0 0 9.175 9.176z");
}

:global(.y2ugsl6kt) {
  cx: 12.701px;
  cy: 24.691px;
  r: 0.75px;
  fill: currentColor;
}

</style>
