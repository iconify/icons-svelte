<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mpa5af89q"/><path class="v6y69ha8m"/><path class="mbt4yzbhr"/><path class="p3knk71rt"/><path class="rn2_dtbur"/><path class="ubbszwy6j"/><path class="z9ittvbis"/><path class="a562fv74t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cliff-duotone-regular" {...props}></Icon>
<style>
:global(.a562fv74t) {
  d: path("M6 22h12");
}

:global(.mbt4yzbhr) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mpa5af89q) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 3h10v13H3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p3knk71rt) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 22h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rn2_dtbur) {
  d: path("M3 3h10v13H3");
}

:global(.ubbszwy6j) {
  d: path("m13 8 4 4v4");
}

:global(.v6y69ha8m) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m13 8 4 4v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

</style>
