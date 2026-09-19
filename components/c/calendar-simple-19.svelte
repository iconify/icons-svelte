<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="m1bwskfbe"/><path class="i3oh-iaco"/></g><g class="y9tr6bcfx"><rect class="w5ztvbg7m"/><path class="w9v12qzbx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:calendar-simple-19" {...props}></Icon>
<style>
:global(.i3oh-iaco) {
  d: path("M24.539 34.025C25.329 35.21 26.71 36 28.883 36h.395a5.31 5.31 0 0 0 5.334-5.333v-5.334M14.28 22.2l4-2.2m0 0v16");
}

:global(.m1bwskfbe) {
  cx: 29.279px;
  cy: 25.333px;
  r: 5.333px;
}

:global(.w5ztvbg7m) {
  width: 35px;
  height: 36px;
  x: 6.5px;
  y: 7.5px;
  rx: 4px;
  ry: 4px;
}

:global(.w9v12qzbx) {
  d: path("M33.5 4.5v6m-19-6v6");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
