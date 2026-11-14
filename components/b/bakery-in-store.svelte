<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xh7h-ac9k"/><path class="yvoouxbhk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bakery-in-store" {...props}></Icon>
<style>
:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xh7h-ac9k) {
  d: path("M3.5 2.5h17v14h-17Zm0 14h17l1 5h-19Z");
}

:global(.yvoouxbhk) {
  d: path("M7.5 13c0-5 9-5 9 0Z");
}

</style>
