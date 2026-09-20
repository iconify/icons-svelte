<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rvz2lnbll"/><path class="e_c8u7_oh"/><path class="rpvgmilnp"/><path class="c44js-bmo"/><path class="paaov7otb"/><path class="keqc2pbxm"/><path class="tuv2qrbve"/><path class="cq9z3jbol"/><path class="l8vricc3a"/><path class="rjbfcabog"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:idempotency-key-duotone-bold" {...props}></Icon>
<style>
:global(.c44js-bmo) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 10h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cq9z3jbol) {
  d: path("M12.5 10v3");
}

:global(.e_c8u7_oh) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 10h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.keqc2pbxm) {
  d: path("M4 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.l8vricc3a) {
  d: path("M17 10h4");
}

:global(.paaov7otb) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 16h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rjbfcabog) {
  d: path("M17 16h4");
}

:global(.rpvgmilnp) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12.5 10v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rvz2lnbll) {
  fill: currentColor;
  d: path("M4 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tuv2qrbve) {
  d: path("M8 10h7");
}

</style>
