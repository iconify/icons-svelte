<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="diipsobkl"/><path class="acyg6nb1v"/><path class="x7iwfqbso"/><path class="bwq8odoli"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pinball-outline-regular" {...props}></Icon>
<style>
:global(.acyg6nb1v) {
  d: path("M10 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.bwq8odoli) {
  d: path("m17 16 -3 3");
}

:global(.diipsobkl) {
  d: path("M5 3v18h14V3Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.x7iwfqbso) {
  d: path("m7 16 3 3");
}

</style>
