<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cafe3oq2n"/><path class="g-mrv1hbe"/><path class="i7xbhqbba"/><path class="ra24a3r4r"/><path class="vddehgbmg"/><path class="ghf6zpb7j"/><path class="x0qn9gsac"/><path class="g7qu0vb4t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:confidence-score-duotone-regular" {...props}></Icon>
<style>
:global(.cafe3oq2n) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m2 14 3 3 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g-mrv1hbe) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 12v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g7qu0vb4t) {
  d: path("M21 14v4");
}

:global(.ghf6zpb7j) {
  d: path("M14 12v6");
}

:global(.i7xbhqbba) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17.5 8v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ra24a3r4r) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M21 14v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vddehgbmg) {
  d: path("m2 14 3 3 5 -5");
}

:global(.x0qn9gsac) {
  d: path("M17.5 8v10");
}

</style>
