<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="srsp9bb6c"/><path class="qsdl_zbij"/><path class="t55yrrbqs"/><path class="r8sldsvbw"/><path class="ltbxi_2yl"/><path class="vru74db2q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:redo-duotone-regular" {...props}></Icon>
<style>
:global(.ltbxi_2yl) {
  d: path("M5 13v5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qsdl_zbij) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 13v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r8sldsvbw) {
  d: path("M5 13a7 7 0 0 1 14 0");
}

:global(.srsp9bb6c) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 13a7 7 0 0 1 14 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t55yrrbqs) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m16 10 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vru74db2q) {
  d: path("m16 10 3 3 3 -3");
}

</style>
