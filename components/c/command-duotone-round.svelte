<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ff2kgro6q"/><path class="oh5ohjntf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:command-duotone-round" {...props}></Icon>
<style>
:global(.ff2kgro6q) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 9H6a3 3 0 1 1 3-3Zm6 0V6a3 3 0 1 1 3 3Zm-6 6v3a3 3 0 1 1-3-3Zm6 0h3a3 3 0 1 1-3 3Z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.oh5ohjntf) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 9V6a3 3 0 1 0-3 3zm6 0V6a3 3 0 1 1 3 3zm0 6v3a3 3 0 1 0 3-3zm-6 0v3a3 3 0 1 1-3-3zm0-6h6v6H9Z");
}

</style>
