<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xenvd-bzf"/><path class="ifgaqkbho"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:reset" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ifgaqkbho) {
  d: path("M14.25 2.25L12 4.5l2.25 2.25");
}

:global(.xenvd-bzf) {
  d: path("M3.5 13A8.5 8.5 0 1 0 12 4.5");
}

</style>
