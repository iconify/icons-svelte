<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hn7tnnbwb"/><path class="p7lotdb8h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:gif" {...props}></Icon>
<style>
:global(.hn7tnnbwb) {
  d: path("M2.5 5h19v14h-19Z");
}

:global(.p7lotdb8h) {
  d: path("M11.5 12a3.5 3.5 0 1 1-1.025-2.475M8.5 12h3m2.25-3.5v7m5.75-7h-3v7m0-3.5H19");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
