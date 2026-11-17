<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h1fn4rz1b"/><path class="c0ysedvtt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:hydrogen-duocolor-round" {...props}></Icon>
<style>
:global(.c0ysedvtt) {
  d: path("M5 13a7 7 0 0 1 14 0v4a4 4 0 0 1-4 4H9a4 4 0 0 1-4-4zm7-7V3m-2 0h4");
}

:global(.h1fn4rz1b) {
  stroke-opacity: 0.4;
  d: path("M9 11v6m6-6v6m-6-3h6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
