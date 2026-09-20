<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pgxan_bzk"/><path class="hb1jglb4j"/><path class="q-mksftst"/><path class="pfioxebak"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:latent-duotone-regular" {...props}></Icon>
<style>
:global(.hb1jglb4j) {
  fill: currentColor;
  d: path("M21 4.5 13.5 12l7.5 7.5Z");
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

:global(.pfioxebak) {
  d: path("M21 4.5 13.5 12l7.5 7.5Z");
}

:global(.pgxan_bzk) {
  fill: currentColor;
  d: path("m3 4.5 7.5 7.5L3 19.5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.q-mksftst) {
  d: path("m3 4.5 7.5 7.5L3 19.5Z");
}

</style>
