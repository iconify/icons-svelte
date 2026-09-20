<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j2r1pso3k"/><path class="lnt75bkgi"/><path class="q6gd3twiv"/><path class="sxlwlmkmh"/><path class="hzsvawc8s"/><path class="u8aszkb6i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:arrow-left-right-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hzsvawc8s) {
  d: path("m8 8 -4 4 4 4");
}

:global(.j2r1pso3k) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 12h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lnt75bkgi) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m8 8 -4 4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.q6gd3twiv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16 8 4 4 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.sxlwlmkmh) {
  d: path("M4 12h16");
}

:global(.u8aszkb6i) {
  d: path("m16 8 4 4 -4 4");
}

</style>
