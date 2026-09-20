<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ve2c5yb5g"/><path class="tpoo0acuc"/><path class="zc40h1bod"/><path class="p_g11-bmp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mfa-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.p_g11-bmp) {
  d: path("M17 18h3");
}

:global(.tpoo0acuc) {
  d: path("M4 8a3 3 0 0 1 6 0");
}

:global(.ve2c5yb5g) {
  d: path("M2 10a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.zc40h1bod) {
  d: path("M15 6a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v13a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
}

</style>
