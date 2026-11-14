<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="swf7gnbxb"/><path class="yb79v5xdl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ppe-station" {...props}></Icon>
<style>
:global(.swf7gnbxb) {
  d: path("M3.5 2.5h17v19h-17Zm0 4.5h17");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yb79v5xdl) {
  d: path("M6.5 16.5h1a4.5 4.5 0 0 1 9 0h1Z");
}

</style>
