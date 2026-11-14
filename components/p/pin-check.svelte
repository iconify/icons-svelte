<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="szgbmkb4d"/><path class="a9-iwj4yd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pin-check" {...props}></Icon>
<style>
:global(.a9-iwj4yd) {
  d: path("M7 8.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm7.75 9.5l2 2L21 15.75");
}

:global(.szgbmkb4d) {
  d: path("M9 19S3.5 14 3.5 8.5a5.5 5.5 0 0 1 11 0C14.5 14 9 19 9 19Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
