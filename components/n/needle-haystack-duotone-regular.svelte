<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k_2z93bzc"/><path class="s1ajs51ib"/><path class="aqrf9ebcv"/><path class="tbe304aqf"/><path class="pga6n1bci"/><path class="mg7aqnbsf"/><path class="vhnbtvbtn"/><path class="n3p0zmbop"/><path class="ys-dg812g"/><path class="jkuojibnm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:needle-haystack-duotone-regular" {...props}></Icon>
<style>
:global(.aqrf9ebcv) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 8h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jkuojibnm) {
  d: path("M3 20h18");
}

:global(.k_2z93bzc) {
  fill: currentColor;
  d: path("M11 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.mg7aqnbsf) {
  d: path("M3 4h18");
}

:global(.n3p0zmbop) {
  d: path("M11 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pga6n1bci) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 20h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s1ajs51ib) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 4h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tbe304aqf) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 16h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vhnbtvbtn) {
  d: path("M3 8h18");
}

:global(.ys-dg812g) {
  d: path("M3 16h18");
}

</style>
