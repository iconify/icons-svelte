<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ytycny5mn"/><path class="pbmx8bajr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:lawn-checkerboard" {...props}></Icon>
<style>
:global(.pbmx8bajr) {
  fill: currentColor;
  d: path("M6.5 4.5H12v7H4.75Zm5.5 7h7.25l2.25 8H12Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ytycny5mn) {
  d: path("M6.5 4.5h11l4 15h-19Z");
}

</style>
