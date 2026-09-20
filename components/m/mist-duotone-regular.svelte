<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jftq2lbbb"/><path class="yxxkvsbzs"/><path class="jdr0a_b0t"/><path class="log_y59fn"/><path class="tzn70zi5q"/><path class="a1aem8u4p"/><path class="nhri7pb9i"/><path class="gsl5knvuq"/><path class="xa52mrrsy"/><path class="e5d_yrbyo"/><path class="z82iob5ig"/><path class="q9naw_b2m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mist-duotone-regular" {...props}></Icon>
<style>
:global(.a1aem8u4p) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.e5d_yrbyo) {
  d: path("M12 13h9");
}

:global(.gsl5knvuq) {
  d: path("M15 8h6");
}

:global(.jdr0a_b0t) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 13h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jftq2lbbb) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 8h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.log_y59fn) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 13h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nhri7pb9i) {
  d: path("M3 8h9");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q9naw_b2m) {
  d: path("M17 18h4");
}

:global(.tzn70zi5q) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 18h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xa52mrrsy) {
  d: path("M3 13h6");
}

:global(.yxxkvsbzs) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 8h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z82iob5ig) {
  d: path("M5 18h9");
}

</style>
