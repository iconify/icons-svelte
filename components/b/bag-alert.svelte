<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="y9tr6bcfx"><g mask="url(#SVGsZ1vtcCp)" class="nl157099w"><path class="o9k8jk4mn"/><path class="dqv2xfb4u"/></g><path class="yr-noebov"/><path class="fxu54sbac"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bag-alert" {...props}></Icon>
<style>
:global(.dqv2xfb4u) {
  d: path("M8.75 9.75V6.5a3.25 3.25 0 0 1 6.5 0v3.25");
}

:global(.fxu54sbac) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.5 20.25h.01");
}

:global(.jf0axzbmx) {
  cx: 17.5px;
  cy: 17.5px;
  r: 6px;
}

:global(.nl157099w) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o9k8jk4mn) {
  d: path("M5.1 8.4a1.75 1.75 0 0 1 1.74-1.65h10.32A1.75 1.75 0 0 1 18.9 8.4l.7 10.3a2.5 2.5 0 0 1-2.5 2.55H6.9a2.5 2.5 0 0 1-2.5-2.55Z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.yr-noebov) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.5 14.5v3.25");
}

</style>
