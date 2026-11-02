<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xsgqi2bof"/><path class="t9id8bcus"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:paint-bucket-duocolor" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.t9id8bcus) {
  d: path("m11 6l6 6l-7 7a1.414 1.414 0 0 1-2 0l-4-4a1.414 1.414 0 0 1 0-2zM8 3l3 3");
}

:global(.xsgqi2bof) {
  stroke-opacity: 0.4;
  d: path("M5 12h12m4 7a2 2 0 1 1-4 0c0-1 1-2 2-3c1 1 2 2 2 3");
}

</style>
