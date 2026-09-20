<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="aqn8oeb4o"/><path class="oq71y_3bz"/><path class="xaz90clio"/><path class="ftolpwp2e"/><path class="fnu2_gbjz"/><path class="tqwo8s6dw"/><path class="mg7aqnbsf"/><path class="j835zw5-z"/><path class="rkhcgsbdl"/><path class="ndv19xfog"/><path class="qypknac_m"/><path class="nlg6c6b-z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:data-augment-duotone-bold" {...props}></Icon>
<style>
:global(.aqn8oeb4o) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 4h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fnu2_gbjz) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16.5 14h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ftolpwp2e) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 14h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.j835zw5-z) {
  d: path("M3 9h18");
}

:global(.mg7aqnbsf) {
  d: path("M3 4h18");
}

:global(.ndv19xfog) {
  d: path("M3 14h10");
}

:global(.nlg6c6b-z) {
  d: path("M18.5 12v4");
}

:global(.oq71y_3bz) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 9h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qypknac_m) {
  d: path("M16.5 14h4");
}

:global(.rkhcgsbdl) {
  d: path("M3 19h18");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tqwo8s6dw) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18.5 12v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xaz90clio) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 19h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
