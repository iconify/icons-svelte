<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z307q5d3s"/><g class="y9tr6bcfx"><circle class="bybjau59l"/><circle class="se87bac5g"/><rect class="brxpxfbzn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:calendar-2" {...props}></Icon>
<style>
:global(.brxpxfbzn) {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  rx: 4px;
  ry: 4px;
}

:global(.bybjau59l) {
  cx: 32.5px;
  cy: 11px;
  r: 2.5px;
}

:global(.se87bac5g) {
  cx: 15.5px;
  cy: 11px;
  r: 2.5px;
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.z307q5d3s) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.765 25.333c0-2.963 2.37-5.333 5.136-5.333s5.334 2.37 5.334 5.333c0 1.383-.593 2.766-1.58 3.753C25.48 30.864 18.764 36 18.764 36h10.47");
}

</style>
