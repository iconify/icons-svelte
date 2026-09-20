<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gms_xv68n"/><path class="i7-hwrk0u"/><path class="yxwh_7bqa"/><path class="bsrnon6so"/><path class="xac31kual"/><path class="r3faxubne"/><path class="ws1d0fbts"/><path class="f3zridcmg"/><path class="z_c7updjp"/><path class="m0msdy1bm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:river-level-duotone-thin" {...props}></Icon>
<style>
:global(.bsrnon6so) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 8h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.f3zridcmg) {
  d: path("m3 14 2.5 -2.5L8 14l2.5 -2.5L13 14l2.5 -2.5L18 14l2.5 -2.5");
}

:global(.gms_xv68n) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i7-hwrk0u) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.m0msdy1bm) {
  d: path("M5 11h4");
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

:global(.ws1d0fbts) {
  d: path("M20 4v16");
}

:global(.xac31kual) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 11h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yxwh_7bqa) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 14 2.5 -2.5L8 14l2.5 -2.5L13 14l2.5 -2.5L18 14l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z_c7updjp) {
  d: path("M5 8h4");
}

</style>
