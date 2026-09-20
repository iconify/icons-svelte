<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hkglpchld"/><path class="bixrf0b_t"/><path class="fgcgcycrv"/><path class="c_pe6njtz"/><path class="bzecsub_a"/><path class="ipr9vreed"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:arrow-left-to-line-duotone-regular" {...props}></Icon>
<style>
:global(.bixrf0b_t) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.bzecsub_a) {
  d: path("M8 12h12");
}

:global(.c_pe6njtz) {
  d: path("M4 7v10");
}

:global(.fgcgcycrv) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m12 8 -4 4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hkglpchld) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ipr9vreed) {
  d: path("m12 8 -4 4 4 4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
