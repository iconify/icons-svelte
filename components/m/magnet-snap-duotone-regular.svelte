<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uevdr0ewy"/><path class="og0086b5o"/><path class="d4-z8scbj"/><path class="if54yrb1r"/><path class="rcka9vbms"/><path class="geu4q150c"/><path class="sa7t2q-eb"/><path class="ek6w2ymjs"/><path class="w7htkxb5b"/><path class="hh2-r7bhw"/><path class="cmb7dmbhv"/><path class="olqp5-9mh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:magnet-snap-duotone-regular" {...props}></Icon>
<style>
:global(.cmb7dmbhv) {
  d: path("M10 3v11");
}

:global(.d4-z8scbj) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 3v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ek6w2ymjs) {
  d: path("M6 3v11");
}

:global(.geu4q150c) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 3v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hh2-r7bhw) {
  d: path("M14 14a2 2 0 0 1 -4 0");
}

:global(.if54yrb1r) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 14a2 2 0 0 1 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.og0086b5o) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 3v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.olqp5-9mh) {
  d: path("M14 3v11");
}

:global(.rcka9vbms) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 3v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.sa7t2q-eb) {
  d: path("M18 14a6 6 0 0 1 -12 0");
}

:global(.uevdr0ewy) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 14a6 6 0 0 1 -12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.w7htkxb5b) {
  d: path("M18 3v11");
}

</style>
