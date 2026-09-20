<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gdy036bip"/><path class="e6h0tjbiq"/><path class="w5li8_bjd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:child-duotone-regular" {...props}></Icon>
<style>
:global(.e6h0tjbiq) {
  d: path("M8 8a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.gdy036bip) {
  fill: currentColor;
  d: path("M8 8a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
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

:global(.w5li8_bjd) {
  d: path("M8 19a4 4 0 0 1 8 0");
}

</style>
