<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w35n61kja"/><path class="ddr0zpdgr"/><path class="uih_zvhtv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:exhibition-outline-thin" {...props}></Icon>
<style>
:global(.ddr0zpdgr) {
  d: path("M8 6a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uih_zvhtv) {
  d: path("M4 21h16");
}

:global(.w35n61kja) {
  d: path("M8 12h8v6H8Z");
}

</style>
