<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="okud9xj_d"/><path class="x26a8iq1c"/><path class="zto18nxmz"/><path class="uue3xmbwl"/><path class="l5m2w6beb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:periodic-table-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l5m2w6beb) {
  d: path("M10 15.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.okud9xj_d) {
  d: path("M2 7a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.uue3xmbwl) {
  d: path("M15 5v14");
}

:global(.x26a8iq1c) {
  d: path("M2 12h20");
}

:global(.zto18nxmz) {
  d: path("M9 5v14");
}

</style>
