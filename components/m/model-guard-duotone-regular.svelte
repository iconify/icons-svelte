<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ufkev6b3p"/><path class="dahm9hfll"/><path class="ag6e_acqq"/><path class="psf2kha1z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:model-guard-duotone-regular" {...props}></Icon>
<style>
:global(.ag6e_acqq) {
  d: path("M6 6.5 9.5 10 6 13.5 2.5 10Z");
}

:global(.dahm9hfll) {
  fill: currentColor;
  d: path("M13 11h9v5.5L17.5 21 13 16.5Z");
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

:global(.psf2kha1z) {
  d: path("M13 11h9v5.5L17.5 21 13 16.5Z");
}

:global(.ufkev6b3p) {
  fill: currentColor;
  d: path("M6 6.5 9.5 10 6 13.5 2.5 10Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
