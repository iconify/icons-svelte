<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xnmffhmjy"/><path class="gn-s3kbpz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:headphones-wireless" {...props}></Icon>
<style>
:global(.gn-s3kbpz) {
  d: path("M8.786 14.67a5 5 0 0 1 6.428 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xnmffhmjy) {
  d: path("M5 13.5v-1a7 7 0 0 1 14 0v1m-16 0h5v7H3Zm13 0h5v7h-5Zm-4 5h.01m-1.778-1.768a2.5 2.5 0 0 1 3.536 0");
}

</style>
