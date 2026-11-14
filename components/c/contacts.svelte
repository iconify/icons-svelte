<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d2812rvmk"/><path class="knium-bvm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:contacts" {...props}></Icon>
<style>
:global(.d2812rvmk) {
  d: path("M3.5 2.5H18v19H3.5Zm14.5 4h2.5M18 12h2.5M18 17.5h2.5");
}

:global(.knium-bvm) {
  d: path("M8.25 9.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM7 17c0-2.25 1.7-3.5 3.75-3.5s3.75 1.25 3.75 3.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
