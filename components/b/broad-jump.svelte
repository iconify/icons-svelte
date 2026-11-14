<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p8ydbtbif"/><path class="rj7vqtkll"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:broad-jump" {...props}></Icon>
<style>
:global(.p8ydbtbif) {
  d: path("M3.5 14a8 8 0 0 1 16 0");
}

:global(.rj7vqtkll) {
  d: path("M17.25 11.75L19.5 14l2.25-2.25M2.5 17.5H9V20h12.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
