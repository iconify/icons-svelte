<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="l5k4yiboy"/><path class="tngfrxbch"/><path class="k_2z93bzc"/><path class="x6ma3nbxt"/><path class="ra5uied2u"/><path class="n3p0zmbop"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:matryoshka-duotone-regular" {...props}></Icon>
<style>
:global(.k_2z93bzc) {
  fill: currentColor;
  d: path("M11 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.l5k4yiboy) {
  fill: currentColor;
  d: path("m12 3 9 9 -9 9 -9 -9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.n3p0zmbop) {
  d: path("M11 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ra5uied2u) {
  d: path("m12 7.5 4.5 4.5 -4.5 4.5L7.5 12Z");
}

:global(.tngfrxbch) {
  fill: currentColor;
  d: path("m12 7.5 4.5 4.5 -4.5 4.5L7.5 12Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.x6ma3nbxt) {
  d: path("m12 3 9 9 -9 9 -9 -9Z");
}

</style>
