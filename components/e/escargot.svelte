<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sz9rzdptz"/><path class="ezoz2c5do"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:escargot" {...props}></Icon>
<style>
:global(.ezoz2c5do) {
  d: path("M3 18h14.5c1.5 0 2.5-1 3-2.5L21 13m-9-4.75a3.25 3.25 0 1 1-3.25 3.25");
}

:global(.sz9rzdptz) {
  d: path("M5.5 11.5a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
