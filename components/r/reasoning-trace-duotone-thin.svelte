<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j8_krc19t"/><path class="r_a6g_bgv"/><path class="n3a0pmdyc"/><path class="c9qt-yqyi"/><path class="g3lrzsbos"/><path class="uepsd3bvn"/><path class="q83h1dbic"/><path class="m_5u0ccez"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:reasoning-trace-duotone-thin" {...props}></Icon>
<style>
:global(.c9qt-yqyi) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 20h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g3lrzsbos) {
  d: path("M3 5h7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j8_krc19t) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 5h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.m_5u0ccez) {
  d: path("M15 20h7");
}

:global(.n3a0pmdyc) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11 15h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.q83h1dbic) {
  d: path("M11 15h7");
}

:global(.r_a6g_bgv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 10h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.uepsd3bvn) {
  d: path("M7 10h7");
}

</style>
