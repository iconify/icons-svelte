<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ley79ielm"/><path class="b28rrzbgr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:flower-shape" {...props}></Icon>
<style>
:global(.b28rrzbgr) {
  d: path("M10.5 12a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

:global(.ley79ielm) {
  d: path("M10.25 9a3.5 3.5 0 1 1 3.5 0a3.5 3.5 0 1 1 1.75 3a3.5 3.5 0 1 1-1.75 3a3.5 3.5 0 1 1-3.5 0a3.5 3.5 0 1 1-1.75-3a3.5 3.5 0 1 1 1.75-3Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
