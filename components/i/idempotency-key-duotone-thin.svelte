<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rvz2lnbll"/><path class="m69rzacut"/><path class="irguiccla"/><path class="rx5svrbnh"/><path class="l12m2cbki"/><path class="keqc2pbxm"/><path class="tuv2qrbve"/><path class="cq9z3jbol"/><path class="l8vricc3a"/><path class="rjbfcabog"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:idempotency-key-duotone-thin" {...props}></Icon>
<style>
:global(.cq9z3jbol) {
  d: path("M12.5 10v3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.irguiccla) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12.5 10v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.keqc2pbxm) {
  d: path("M4 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.l12m2cbki) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 16h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.l8vricc3a) {
  d: path("M17 10h4");
}

:global(.m69rzacut) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 10h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rjbfcabog) {
  d: path("M17 16h4");
}

:global(.rvz2lnbll) {
  fill: currentColor;
  d: path("M4 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.rx5svrbnh) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 10h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tuv2qrbve) {
  d: path("M8 10h7");
}

</style>
