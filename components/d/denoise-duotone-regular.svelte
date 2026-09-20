<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="asz-ftbxh"/><path class="zo_l4ub5r"/><path class="iulb4mb6k"/><path class="z35tx4bdc"/><path class="mqnae981n"/><path class="oifr9zbpt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:denoise-duotone-regular" {...props}></Icon>
<style>
:global(.asz-ftbxh) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 6 4 -4 4 4 4 -4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.iulb4mb6k) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mqnae981n) {
  d: path("m9 11 3 3 3 -3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.z35tx4bdc) {
  d: path("m3 6 4 -4 4 4 4 -4 4 4");
}

:global(.zo_l4ub5r) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 11 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
