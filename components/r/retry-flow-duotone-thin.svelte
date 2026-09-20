<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r8kprgqqs"/><path class="f21or-k3k"/><path class="gujomac1p"/><path class="d398-sb-v"/><path class="q4dmh0yls"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:retry-flow-duotone-thin" {...props}></Icon>
<style>
:global(.d398-sb-v) {
  d: path("M17.5 10.67a5 5 0 1 1 -5 0");
}

:global(.f21or-k3k) {
  d: path("M2 4a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.gujomac1p) {
  d: path("M6 10v6h4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.q4dmh0yls) {
  d: path("M11 9.5h3v3");
}

:global(.r8kprgqqs) {
  fill: currentColor;
  d: path("M2 4a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
