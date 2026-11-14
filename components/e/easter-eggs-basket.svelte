<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qy5wglbwk"/><path class="ksxg8tj4u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:easter-eggs-basket" {...props}></Icon>
<style>
:global(.ksxg8tj4u) {
  d: path("M6.75 12c0-4 3.25-4 3.25 0m0 0c0-5.5 4-5.5 4 0m0 0c0-4 3.25-4 3.25 0");
}

:global(.qy5wglbwk) {
  d: path("M2.5 12h19l-2 7a2 2 0 0 1-2 1.5h-11a2 2 0 0 1-2-1.5ZM4 12C4 1 20 1 20 12");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
