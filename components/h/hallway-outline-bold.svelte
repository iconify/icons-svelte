<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="oviqrkboq"/><path class="maf2tbbex"/><path class="oqfv9rb9x"/><path class="g-g6w6buq"/><path class="me7c_bbry"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:hallway-outline-bold" {...props}></Icon>
<style>
:global(.g-g6w6buq) {
  d: path("M7 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.maf2tbbex) {
  d: path("M15 4h6v14h-6Z");
}

:global(.me7c_bbry) {
  d: path("M15 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.oqfv9rb9x) {
  d: path("M2 21h20");
}

:global(.oviqrkboq) {
  d: path("M3 4h6v14H3Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
