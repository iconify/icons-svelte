<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r_rndyb3y"/><path class="zdz2kgb9i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:houseboat" {...props}></Icon>
<style>
:global(.r_rndyb3y) {
  d: path("M3 16h18l-2.5 4h-13Zm3-8l6-4l6 4v8H6Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zdz2kgb9i) {
  d: path("M10.5 11h3v5h-3Z");
}

</style>
