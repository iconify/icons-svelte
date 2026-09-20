<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w395fxb3e"/><path class="tcxfk34nj"/><path class="xsyfe-byx"/><path class="ehef6tbzw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:paint-palette-outline-regular" {...props}></Icon>
<style>
:global(.ehef6tbzw) {
  d: path("M10 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tcxfk34nj) {
  d: path("M7 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.w395fxb3e) {
  d: path("M12 3a9 9 0 1 0 0 18 2.5 2.5 0 0 0 0 -5 2 2 0 0 1 0 -4h5a4 4 0 0 0 4 -4c0 -3 -4 -5 -9 -5");
}

:global(.xsyfe-byx) {
  d: path("M6 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
