<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iv1n8gbar"/><path class="mwf5pf3ps"/><path class="o1d_6eb1p"/><path class="ghpezkxlh"/><path class="ffv1x3til"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:body-temperature-duotone-thin" {...props}></Icon>
<style>
:global(.ffv1x3til) {
  d: path("M15 4a6 6 0 0 1 0 12");
}

:global(.ghpezkxlh) {
  d: path("M15 7a3 3 0 0 1 0 6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iv1n8gbar) {
  fill: currentColor;
  d: path("M6 18a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.mwf5pf3ps) {
  d: path("M9 4v11");
}

:global(.o1d_6eb1p) {
  d: path("M6 18a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
