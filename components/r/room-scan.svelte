<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yt_4_pnkq"/><path class="ig5rxfb8s"/><path class="h_wb1wqlm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:room-scan" {...props}></Icon>
<style>
:global(.h_wb1wqlm) {
  d: path("M14 21v-5.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ig5rxfb8s) {
  fill: currentColor;
  d: path("m3 3l7.75 3.25a8.4 8.4 0 0 1-4.5 4.5Z");
}

:global(.yt_4_pnkq) {
  d: path("M4.5 3h15A1.5 1.5 0 0 1 21 4.5v15a1.5 1.5 0 0 1-1.5 1.5h-15A1.5 1.5 0 0 1 3 19.5v-15A1.5 1.5 0 0 1 4.5 3");
}

</style>
