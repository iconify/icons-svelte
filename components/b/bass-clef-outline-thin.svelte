<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vbvr2ebxa"/><path class="uk0rveqaj"/><path class="xcm-54bzl"/><path class="a6m5kfb7k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bass-clef-outline-thin" {...props}></Icon>
<style>
:global(.a6m5kfb7k) {
  d: path("M18 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uk0rveqaj) {
  d: path("M4 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.vbvr2ebxa) {
  d: path("M7 6c4 0 8 2 8 6s-4 7 -8 8");
}

:global(.xcm-54bzl) {
  d: path("M18 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
