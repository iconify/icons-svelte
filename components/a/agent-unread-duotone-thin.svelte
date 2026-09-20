<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bcnz89gqx"/><path class="jft30l2oy"/><path class="z3ru5llvg"/><path class="fadcahsis"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-unread-duotone-thin" {...props}></Icon>
<style>
:global(.bcnz89gqx) {
  fill: currentColor;
  d: path("M18 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.fadcahsis) {
  d: path("M18 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jft30l2oy) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13.96 6.66a7 7 0 1 1 -5.92 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z3ru5llvg) {
  d: path("M13.96 6.66a7 7 0 1 1 -5.92 0");
}

</style>
