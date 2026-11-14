<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mk5xfob2d"/><path class="ro66i3beg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:location-history" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mk5xfob2d) {
  d: path("M5 12a8 8 0 1 1 4 6.928");
}

:global(.ro66i3beg) {
  d: path("m2 9l3 3l3-3m5 7s-3.5-3-3.5-5.25a3.5 3.5 0 0 1 7 0C16.5 13 13 16 13 16");
}

</style>
