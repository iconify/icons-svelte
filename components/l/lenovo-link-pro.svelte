<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nl429upab"/><path class="a0gx2mjgh"/><path class="ao9swxb1q"/><circle class="vslyb9bgk"/><circle class="aq5re3bid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:lenovo-link-pro" {...props}></Icon>
<style>
:global(.a0gx2mjgh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.367 7.397v29.031h21.44");
}

:global(.ao9swxb1q) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.439 5.5v24.856h17.266");
}

:global(.aq5re3bid) {
  cx: 37.756px;
  cy: 36.428px;
  r: 0.949px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.nl429upab) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.295 5.5v37h29.41");
}

:global(.vslyb9bgk) {
  cx: 15.367px;
  cy: 6.449px;
  r: 0.949px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
