<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kppldlbxi"/><path class="j0_gtur-i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:package-deprecated" {...props}></Icon>
<style>
:global(.j0_gtur-i) {
  d: path("m3 7l9 4.5L21 7m-9 4.5v4.1m0 .3v5.6m3-3.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm.75-2.25l4.5 4.5");
}

:global(.kppldlbxi) {
  d: path("M13.006 20.997L12 21.5L3 17V7l9-4.5L21 7v6.038");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
