<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i3cv35p_l"/><path class="ktxjg3b2q"/><path class="evsu0jbbm"/><path class="drjad9bfe"/><path class="rgnpgnbjr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pet-grooming-outline-regular" {...props}></Icon>
<style>
:global(.drjad9bfe) {
  d: path("M14 14v4");
}

:global(.evsu0jbbm) {
  d: path("M10 14v4");
}

:global(.i3cv35p_l) {
  d: path("M4 8a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

:global(.ktxjg3b2q) {
  d: path("M6 14v4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rgnpgnbjr) {
  d: path("M16 10h5");
}

</style>
