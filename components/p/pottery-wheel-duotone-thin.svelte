<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q2602seyu"/><path class="hya5w9myb"/><path class="ys-dg812g"/><path class="fmlaifbpn"/><path class="qdn88l2uv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pottery-wheel-duotone-thin" {...props}></Icon>
<style>
:global(.fmlaifbpn) {
  d: path("M12 16v4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hya5w9myb) {
  d: path("M9 13c-2 -2 -1 -5 1 -7h4c2 2 3 5 1 7Z");
}

:global(.q2602seyu) {
  fill: currentColor;
  d: path("M9 13c-2 -2 -1 -5 1 -7h4c2 2 3 5 1 7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.qdn88l2uv) {
  d: path("M7 20h10");
}

:global(.ys-dg812g) {
  d: path("M3 16h18");
}

</style>
