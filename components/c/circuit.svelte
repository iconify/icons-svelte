<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v-okrzb7m"/><circle class="rip_g9cqu"/><path class="q9-aapbwy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:circuit" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.q9-aapbwy) {
  d: path("M10.5 2.75v4m3-3v2");
}

:global(.rip_g9cqu) {
  cx: 12px;
  cy: 19.25px;
  r: 2px;
}

:global(.v-okrzb7m) {
  d: path("M10.5 4.75H6.25a2.5 2.5 0 0 0-2.5 2.5v9.5a2.5 2.5 0 0 0 2.5 2.5H10m3.5-14.5h4.25a2.5 2.5 0 0 1 2.5 2.5v9.5a2.5 2.5 0 0 1-2.5 2.5H14");
}

</style>
