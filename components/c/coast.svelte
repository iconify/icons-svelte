<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="olfenrkki"/><path class="d5z8kbc0g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:coast" {...props}></Icon>
<style>
:global(.d5z8kbc0g) {
  d: path("M11.5 11q2.25-1.5 4.5 0t4.5 0");
}

:global(.olfenrkki) {
  d: path("M2.5 2.5H9c2.5 1.5 2.5 4 .5 5.5c-3 2-3 5 .5 6.5c3 1 5.5 2.5 5.5 7h-13Zm12 3q1.75-1.5 3.5 0t3.5 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
