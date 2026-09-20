<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="askgmhbjk"/><path class="t5z055brv"/><path class="adx_66b5y"/><path class="w2dozdlxo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:primary-key-outline-thin" {...props}></Icon>
<style>
:global(.adx_66b5y) {
  d: path("M13 7v3");
}

:global(.askgmhbjk) {
  d: path("M3 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.t5z055brv) {
  d: path("M7 7h8");
}

:global(.w2dozdlxo) {
  d: path("M2 14a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
