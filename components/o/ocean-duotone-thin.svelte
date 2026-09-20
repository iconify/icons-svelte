<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="roppagcur"/><path class="la3ztabeg"/><path class="w1gxsil6l"/><path class="lmj_kj__f"/><path class="oy_r10b4z"/><path class="yzilgtbzd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ocean-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.la3ztabeg) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 14 3 -3 3 3 3 -3 3 3 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lmj_kj__f) {
  d: path("m3 8 3 -3 3 3 3 -3 3 3 3 -3 3 3");
}

:global(.oy_r10b4z) {
  d: path("m3 14 3 -3 3 3 3 -3 3 3 3 -3 3 3");
}

:global(.roppagcur) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 8 3 -3 3 3 3 -3 3 3 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.w1gxsil6l) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 20 3 -3 3 3 3 -3 3 3 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yzilgtbzd) {
  d: path("m3 20 3 -3 3 3 3 -3 3 3 3 -3 3 3");
}

</style>
