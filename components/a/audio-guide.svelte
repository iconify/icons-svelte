<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ukg0kpkum"/><path class="s6r0hppzp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:audio-guide" {...props}></Icon>
<style>
:global(.s6r0hppzp) {
  d: path("M3.5 12.5H8v7H3.5Zm12.5 0h4.5v7H16Z");
}

:global(.ukg0kpkum) {
  d: path("M4.5 13v-1a7.5 7.5 0 0 1 15 0v1");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
