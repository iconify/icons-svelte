<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vq0uixb9a"/><path class="h3nfybbey"/><path class="vl-78uvmi"/><path class="i72p9bc3o"/><path class="rpp4spbxo"/><path class="k4wc6x-hq"/><path class="n_xjdobth"/><path class="ghuq2xb5p"/><path class="cjtmbcfpi"/><path class="bod4n0b3z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:resort-duotone-thin" {...props}></Icon>
<style>
:global(.bod4n0b3z) {
  d: path("M2 18h20");
}

:global(.cjtmbcfpi) {
  d: path("M13 18v-7h9v7");
}

:global(.ghuq2xb5p) {
  d: path("M10.5 12.5a3.5 3.5 0 0 1 0 -7");
}

:global(.h3nfybbey) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3.5 5.5a3.5 3.5 0 0 1 0 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i72p9bc3o) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 18v-7h9v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k4wc6x-hq) {
  d: path("M7 9v9");
}

:global(.n_xjdobth) {
  d: path("M3.5 5.5a3.5 3.5 0 0 1 0 7");
}

:global(.rpp4spbxo) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 18h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vl-78uvmi) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10.5 12.5a3.5 3.5 0 0 1 0 -7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vq0uixb9a) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 9v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
