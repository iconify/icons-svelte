<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qh3x50ajr"/><path class="bmzq19b2x"/><path class="a-v3knb-a"/><path class="qbq59yb6c"/><path class="bac4tq45c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:business-trip-duotone-thin" {...props}></Icon>
<style>
:global(.a-v3knb-a) {
  d: path("M3 14a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.bac4tq45c) {
  d: path("m11 2 2.5 2.5H19L16.5 7H11Z");
}

:global(.bmzq19b2x) {
  fill: currentColor;
  d: path("m11 2 2.5 2.5H19L16.5 7H11Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qbq59yb6c) {
  d: path("M9 12V9.5h6V12");
}

:global(.qh3x50ajr) {
  fill: currentColor;
  d: path("M3 14a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
