<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dgcw4wxkq"/><path class="omo0fdcrs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:first-contact" {...props}></Icon>
<style>
:global(.dgcw4wxkq) {
  d: path("M3 11a9 3 0 1 0 18 0a9 3 0 1 0-18 0Z");
}

:global(.omo0fdcrs) {
  d: path("M7.5 8.5a4.5 4.5 0 0 1 9 0M4 20h16");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
