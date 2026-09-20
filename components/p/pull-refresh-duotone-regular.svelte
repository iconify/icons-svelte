<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lfzh_fbfy"/><path class="dlipkccvb"/><path class="q46ar0blg"/><path class="dd2oi04rr"/><path class="edr2cqsrt"/><path class="juej44_6j"/><path class="yih0nfb7c"/><path class="rkhcgsbdl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pull-refresh-duotone-regular" {...props}></Icon>
<style>
:global(.dd2oi04rr) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 19h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dlipkccvb) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9.5 7.5 12 10l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.edr2cqsrt) {
  d: path("M9.5 3 12 5.5 14.5 3");
}

:global(.juej44_6j) {
  d: path("M9.5 7.5 12 10l2.5 -2.5");
}

:global(.lfzh_fbfy) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9.5 3 12 5.5 14.5 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q46ar0blg) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 14h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rkhcgsbdl) {
  d: path("M3 19h18");
}

:global(.yih0nfb7c) {
  d: path("M3 14h18");
}

</style>
