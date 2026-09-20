<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cwv1j_bei"/><path class="mbt4yzbhr"/><path class="z5cj28bhd"/><path class="z9ittvbis"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mountain-duotone-regular" {...props}></Icon>
<style>
:global(.cwv1j_bei) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m2 16 6 -6 3 3 4 -4 7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mbt4yzbhr) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.z5cj28bhd) {
  d: path("m2 16 6 -6 3 3 4 -4 7 7");
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

</style>
