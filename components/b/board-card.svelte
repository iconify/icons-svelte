<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xc153x4nr"/><path class="rky29dr0f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:board-card" {...props}></Icon>
<style>
:global(.rky29dr0f) {
  d: path("M10 6.25h4v6h-4Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xc153x4nr) {
  d: path("M2.5 3.5h19v17h-19Zm5 0v17m9-17v17");
}

</style>
