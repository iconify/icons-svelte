<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b32qokucr"/><path class="usr9unc6p"/><path class="x3sflacnk"/><path class="p937wxhzi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:idea-bulb-duotone-regular" {...props}></Icon>
<style>
:global(.b32qokucr) {
  fill: currentColor;
  d: path("M8 12a6 6 0 1 1 8 0v3H8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p937wxhzi) {
  d: path("M10 21h4");
}

:global(.usr9unc6p) {
  d: path("M8 12a6 6 0 1 1 8 0v3H8Z");
}

:global(.x3sflacnk) {
  d: path("M9 18h6");
}

</style>
