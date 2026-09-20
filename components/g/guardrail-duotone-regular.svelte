<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zhgf1vz5u"/><path class="c0i67abdl"/><path class="n7hofvu8z"/><path class="tkeq0bpvv"/><path class="yw-dgs_nk"/><path class="ivdpkbnwt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:guardrail-duotone-regular" {...props}></Icon>
<style>
:global(.c0i67abdl) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ivdpkbnwt) {
  d: path("m11 9 3 3 -3 3");
}

:global(.n7hofvu8z) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m11 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tkeq0bpvv) {
  d: path("M18 4v16");
}

:global(.yw-dgs_nk) {
  d: path("M4 12h10");
}

:global(.zhgf1vz5u) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
