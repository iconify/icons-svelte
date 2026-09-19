<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ac35tpbkl"/><g class="y9tr6bcfx"><circle class="bybjau59l"/><circle class="se87bac5g"/><rect class="brxpxfbzn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:calendar-8" {...props}></Icon>
<style>
:global(.ac35tpbkl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.3 28h-2.6c-2.2 0-4 1.8-4 4h0c0 2.2 1.8 4 4 4h2.6c2.2 0 4-1.8 4-4h0c0-2.2-1.8-4-4-4m0 0c2.2 0 4-1.8 4-4h0c0-2.2-1.8-4-4-4h-2.6c-2.2 0-4 1.8-4 4h0c0 2.2 1.8 4 4 4");
}

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

</style>
