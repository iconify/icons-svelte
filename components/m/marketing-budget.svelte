<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="woctahbxr"/><path class="c-ibc-_xn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:marketing-budget" {...props}></Icon>
<style>
:global(.c-ibc-_xn) {
  d: path("M13.5 10.25v-8a8 8 0 0 1 8 8Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.woctahbxr) {
  d: path("M10.75 5a8 8 0 1 0 8 8h-8Z");
}

</style>
