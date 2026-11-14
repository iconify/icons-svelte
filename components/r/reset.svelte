<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xenvd-bzf"/><path class="ifgaqkbho"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:reset" {...props}></Icon>
<style>
:global(.ifgaqkbho) {
  d: path("M14.25 2.25L12 4.5l2.25 2.25");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xenvd-bzf) {
  d: path("M3.5 13A8.5 8.5 0 1 0 12 4.5");
}

</style>
