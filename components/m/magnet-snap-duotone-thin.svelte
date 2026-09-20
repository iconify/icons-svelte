<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="crh41zgek"/><path class="jo2qgdb_s"/><path class="qj7cj8bka"/><path class="i523cabkd"/><path class="qvbsohboi"/><path class="s6jmbp3oh"/><path class="sa7t2q-eb"/><path class="ek6w2ymjs"/><path class="w7htkxb5b"/><path class="hh2-r7bhw"/><path class="cmb7dmbhv"/><path class="olqp5-9mh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:magnet-snap-duotone-thin" {...props}></Icon>
<style>
:global(.cmb7dmbhv) {
  d: path("M10 3v11");
}

:global(.crh41zgek) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 14a6 6 0 0 1 -12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ek6w2ymjs) {
  d: path("M6 3v11");
}

:global(.hh2-r7bhw) {
  d: path("M14 14a2 2 0 0 1 -4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i523cabkd) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 14a2 2 0 0 1 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jo2qgdb_s) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 3v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.olqp5-9mh) {
  d: path("M14 3v11");
}

:global(.qj7cj8bka) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 3v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qvbsohboi) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 3v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s6jmbp3oh) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 3v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.sa7t2q-eb) {
  d: path("M18 14a6 6 0 0 1 -12 0");
}

:global(.w7htkxb5b) {
  d: path("M18 3v11");
}

</style>
