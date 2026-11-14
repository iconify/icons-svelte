<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mhuvow97a"/><path class="ulrfqkbof"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:digital-cluster" {...props}></Icon>
<style>
:global(.mhuvow97a) {
  d: path("M2.5 5.5h19v13h-19Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ulrfqkbof) {
  d: path("M9 18.5a4 4 0 0 1 0-8m0 4l2.5-2.5M17 9.5V15");
}

</style>
