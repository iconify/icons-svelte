<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d5c02v83h"/><path class="ghebrcc5x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:chart-title" {...props}></Icon>
<style>
:global(.d5c02v83h) {
  fill: currentColor;
  d: path("M2.5 2.5h12V6h-12Z");
}

:global(.ghebrcc5x) {
  d: path("M2.5 21.5h19M3 18.5l4.5-6l4 3l4.5-6l5 3.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
