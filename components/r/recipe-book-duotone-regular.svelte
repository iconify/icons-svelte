<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x5ujzyh2u"/><path class="txlppcctn"/><path class="uk66x15py"/><path class="wuvisubmw"/><path class="eiprk3b7d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:recipe-book-duotone-regular" {...props}></Icon>
<style>
:global(.eiprk3b7d) {
  d: path("M11 10h6c0 2.5 -1.5 4 -3 4s-3 -1.5 -3 -4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.txlppcctn) {
  fill: currentColor;
  d: path("M11 10h6c0 2.5 -1.5 4 -3 4s-3 -1.5 -3 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.uk66x15py) {
  d: path("M4 3v18h16V3Z");
}

:global(.wuvisubmw) {
  d: path("M8 3v18");
}

:global(.x5ujzyh2u) {
  fill: currentColor;
  d: path("M4 3v18h16V3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
