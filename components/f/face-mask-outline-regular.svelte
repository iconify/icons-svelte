<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yoftwf7ei"/><path class="gqwusxz8h"/><path class="mbifgmx_w"/><path class="tp86gnbwd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:face-mask-outline-regular" {...props}></Icon>
<style>
:global(.gqwusxz8h) {
  d: path("M3 12h18v3a12 12 0 0 1 -18 0Z");
}

:global(.mbifgmx_w) {
  d: path("M3 12V8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tp86gnbwd) {
  d: path("M21 12V8");
}

:global(.yoftwf7ei) {
  d: path("M6 9a6 6 0 1 0 12 0A6 6 0 1 0 6 9");
}

</style>
