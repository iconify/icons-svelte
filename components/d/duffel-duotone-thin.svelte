<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k6v6_yp7k"/><path class="oiiy8u_cj"/><path class="j68wzwbiz"/><path class="vxy4ztabh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:duffel-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j68wzwbiz) {
  d: path("M8 9a4 4 0 0 1 8 0");
}

:global(.k6v6_yp7k) {
  fill: currentColor;
  d: path("M4 9h16a3 3 0 0 1 0 10H4A3 3 0 0 1 4 9");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.oiiy8u_cj) {
  d: path("M4 9h16a3 3 0 0 1 0 10H4A3 3 0 0 1 4 9");
}

:global(.vxy4ztabh) {
  d: path("M4 14h16");
}

</style>
