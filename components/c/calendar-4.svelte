<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xmkssvbkk"/><g class="y9tr6bcfx"><circle class="bybjau59l"/><circle class="se87bac5g"/><rect class="brxpxfbzn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:calendar-4" {...props}></Icon>
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

:global(.xmkssvbkk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.3 36V20l-8.6 10.8h10.6");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
