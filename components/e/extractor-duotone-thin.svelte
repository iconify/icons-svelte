<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g9u082bkk"/><path class="g2qe3ubhz"/><path class="q3dlgtfea"/><path class="rzyhl__ak"/><path class="gv3gpab3b"/><path class="o7xcj9b5m"/><path class="iu3j18b-o"/><path class="izkbhz86a"/><path class="cfyvl-o0i"/><path class="mi_m6achy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:extractor-duotone-thin" {...props}></Icon>
<style>
:global(.cfyvl-o0i) {
  d: path("M16 12h4");
}

:global(.g2qe3ubhz) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 8h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g9u082bkk) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 2H6v19h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gv3gpab3b) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m17 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iu3j18b-o) {
  d: path("M9 8h4");
}

:global(.izkbhz86a) {
  d: path("M9 12h4");
}

:global(.mi_m6achy) {
  d: path("m17 9 3 3 -3 3");
}

:global(.o7xcj9b5m) {
  d: path("M13 2H6v19h8");
}

:global(.q3dlgtfea) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 12h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rzyhl__ak) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 12h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
