<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xukyidbyw"/><path class="qjaxl2bjn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:auto-wipers" {...props}></Icon>
<style>
:global(.qjaxl2bjn) {
  d: path("M6.076 14.368A5 5 0 0 1 8.5 9.17m7.25 12.58l3-6.5l3 6.5M17 19h3.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xukyidbyw) {
  d: path("M15.584 15.5H3l1.5-11q7-1.5 14 0l.705 5.17M11 13.5L6.5 7");
}

</style>
