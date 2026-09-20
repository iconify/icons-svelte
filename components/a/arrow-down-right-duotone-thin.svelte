<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k46pmtl2a"/><path class="w1rs6qnox"/><path class="po51cnplk"/><path class="cejwj-bns"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:arrow-down-right-duotone-thin" {...props}></Icon>
<style>
:global(.cejwj-bns) {
  d: path("M10 20h10V10");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k46pmtl2a) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m4 4 16 16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.po51cnplk) {
  d: path("m4 4 16 16");
}

:global(.w1rs6qnox) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 20h10V10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
