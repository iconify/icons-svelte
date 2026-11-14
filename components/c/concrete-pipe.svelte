<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nv-mrbc3l"/><path class="a4eabq4db"/><path class="w7gw16bww"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:concrete-pipe" {...props}></Icon>
<style>
:global(.a4eabq4db) {
  d: path("M3 11a4 7 0 1 0 8 0a4 7 0 1 0-8 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nv-mrbc3l) {
  d: path("M7 4h10a4 7 0 0 1 0 14H7");
}

:global(.w7gw16bww) {
  d: path("M5.75 11a1.25 4 0 1 0 2.5 0a1.25 4 0 1 0-2.5 0M2.5 20.75h19");
}

</style>
