<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="wabik_blp"/><path class="xonbz1wvv"/><path class="tbfk_ufxn"/><path class="i01nrr18t"/><path class="jiw8u-asa"/><path class="hwmj2eixw"/><path class="m0wo8tb6s"/><path class="ulyohmb5e"/><path class="u7sb4-hdn"/><path class="oifr9zbpt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:counter-metric-duotone-bold" {...props}></Icon>
<style>
:global(.hwmj2eixw) {
  d: path("M7 8.5v9");
}

:global(.i01nrr18t) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m14.5 13 2.5 2.5 2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jiw8u-asa) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.m0wo8tb6s) {
  d: path("M4.5 9 7 6.5 9.5 9");
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tbfk_ufxn) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 6.5v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.u7sb4-hdn) {
  d: path("m14.5 13 2.5 2.5 2.5 -2.5");
}

:global(.ulyohmb5e) {
  d: path("M17 6.5v9");
}

:global(.wabik_blp) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 8.5v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xonbz1wvv) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4.5 9 7 6.5 9.5 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
