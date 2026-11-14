<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uet0sjbbr"/><path class="xtu6j3b1r"/><path class="xkiburbct"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:head-tracked-audio" {...props}></Icon>
<style>
:global(.uet0sjbbr) {
  d: path("M9 21.5v-3c-1.75-1.25-2.5-3.25-2.5-5.25C6.5 10 8.75 7.5 12 7.5c3 0 5.25 2 5.25 5.25l1.25 2.5q0 .75-.75.75h-.5v1.75c0 .75-.75 1.5-1.5 1.5h-1.5v2.25");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xkiburbct) {
  d: path("m17.5 7l2.5.25l.25-2.5");
}

:global(.xtu6j3b1r) {
  d: path("M10 11.25h3.5v5H10Zm-6-4a10.5 10.5 0 0 1 16 0");
}

</style>
