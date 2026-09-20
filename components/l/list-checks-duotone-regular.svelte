<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lau918bij"/><path class="lqrxlsb_g"/><path class="fhwho7lqi"/><path class="gbmxeebre"/><path class="x69yfdbvx"/><path class="ojrc16bxu"/><path class="dm_ar8wjk"/><path class="z5u11lbdo"/><path class="z4f7qacqo"/><path class="g9c4ykb9u"/><path class="myi37dz6l"/><path class="syk7o8b5x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:list-checks-duotone-regular" {...props}></Icon>
<style>
:global(.dm_ar8wjk) {
  d: path("m3 7 2 2 3 -3");
}

:global(.fhwho7lqi) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 12 2 2 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g9c4ykb9u) {
  d: path("M11 12h10");
}

:global(.gbmxeebre) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M11 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lau918bij) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 7 2 2 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lqrxlsb_g) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M11 7h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.myi37dz6l) {
  d: path("m3 17 2 2 3 -3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ojrc16bxu) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M11 17h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.syk7o8b5x) {
  d: path("M11 17h10");
}

:global(.x69yfdbvx) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 17 2 2 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z4f7qacqo) {
  d: path("m3 12 2 2 3 -3");
}

:global(.z5u11lbdo) {
  d: path("M11 7h10");
}

</style>
