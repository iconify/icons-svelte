<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i4u9dxbqm"/><path class="bb278gpil"/><path class="kllnjy40b"/><path class="ytw5afb0h"/><path class="xtjp0b80d"/><path class="frofbtbej"/><path class="dxdpz6gbz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:champagne-duotone-regular" {...props}></Icon>
<style>
:global(.bb278gpil) {
  fill: currentColor;
  d: path("M14 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.dxdpz6gbz) {
  d: path("M17 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.frofbtbej) {
  d: path("M14 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.i4u9dxbqm) {
  fill: currentColor;
  d: path("M5 21v-8c0 -2 1 -3 1 -5V5h4v3c0 2 1 3 1 5v8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.kllnjy40b) {
  fill: currentColor;
  d: path("M17 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.xtjp0b80d) {
  d: path("M6 5V2h4v3");
}

:global(.ytw5afb0h) {
  d: path("M5 21v-8c0 -2 1 -3 1 -5V5h4v3c0 2 1 3 1 5v8Z");
}

</style>
