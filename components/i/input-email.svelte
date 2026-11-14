<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="em4j34a7u"/><path class="hutb108ig"/><path class="f7uah9_3n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:input-email" {...props}></Icon>
<style>
:global(.em4j34a7u) {
  d: path("M2.5 6h19v12h-19Z");
}

:global(.f7uah9_3n) {
  d: path("M10 10.5v2.25c0 .85.6 1.25 1.25 1.25c.75 0 1.25-1 1.25-2a4 4 0 1 0-1.5 3m4.5-3h3");
}

:global(.hutb108ig) {
  d: path("M7 12a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
