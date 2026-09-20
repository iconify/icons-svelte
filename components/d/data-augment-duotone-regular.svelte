<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s1ajs51ib"/><path class="dx4yo_bup"/><path class="dd2oi04rr"/><path class="bww646bld"/><path class="j_cm6er4j"/><path class="ha74cs_zj"/><path class="mg7aqnbsf"/><path class="j835zw5-z"/><path class="rkhcgsbdl"/><path class="ndv19xfog"/><path class="qypknac_m"/><path class="nlg6c6b-z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:data-augment-duotone-regular" {...props}></Icon>
<style>
:global(.bww646bld) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 14h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dd2oi04rr) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 19h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dx4yo_bup) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 9h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ha74cs_zj) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18.5 12v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.j_cm6er4j) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16.5 14h4");
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

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qypknac_m) {
  d: path("M16.5 14h4");
}

:global(.rkhcgsbdl) {
  d: path("M3 19h18");
}

:global(.s1ajs51ib) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 4h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
