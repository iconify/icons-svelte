<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c8v1jhnro"/><path class="a6k62accz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:library-building-clock" {...props}></Icon>
<style>
:global(.a6k62accz) {
  d: path("M18 16.5V18l1.25 1");
}

:global(.c8v1jhnro) {
  d: path("M3 8.5L12 3l9 5.5ZM3 21h9.7m-6.2-9.5V18m5-6.5V18m3.25 0a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
