<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j7ydteo0d"/><path class="pqlbb9zeg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:compare-options" {...props}></Icon>
<style>
:global(.j7ydteo0d) {
  d: path("M2.5 3h8v18h-8Zm11 0h8v18h-8Z");
}

:global(.pqlbb9zeg) {
  d: path("m16 12.5l1.5 1.5l1.5-2.75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
