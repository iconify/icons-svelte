<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="m1bwskfbe"/><path class="i3oh-iaco"/></g><g class="y9tr6bcfx"><circle class="bybjau59l"/><circle class="se87bac5g"/><rect class="brxpxfbzn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:calendar-19" {...props}></Icon>
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

:global(.i3oh-iaco) {
  d: path("M24.539 34.025C25.329 35.21 26.71 36 28.883 36h.395a5.31 5.31 0 0 0 5.334-5.333v-5.334M14.28 22.2l4-2.2m0 0v16");
}

:global(.m1bwskfbe) {
  cx: 29.279px;
  cy: 25.333px;
  r: 5.333px;
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

</style>
