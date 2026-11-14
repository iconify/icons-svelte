<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dii787b-r"/><path class="r0x6ycc2a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cute-chick" {...props}></Icon>
<style>
:global(.dii787b-r) {
  d: path("m4.5 12.25l2.5 2.5l2.5-2.5l2.5 2.5l2.5-2.5l2.5 2.5l2.5-2.5c0 5.5-3.25 8.5-7.5 8.5s-7.5-3-7.5-8.5Zm5 0a4.75 4.75 0 1 1 5 0");
}

:global(.r0x6ycc2a) {
  d: path("M16.75 6.75L20 8.25l-3.25 1.5Zm-3.5.25h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
