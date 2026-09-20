<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="usr9unc6p"/><path class="x3sflacnk"/><path class="p937wxhzi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:idea-bulb-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
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
