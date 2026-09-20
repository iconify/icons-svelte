<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ju0sk_7wf"/><path class="ziznm1ama"/><path class="z9ittvbis"/><path class="it83nbbll"/><path class="dxdpz6gbz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dj-outline-thin" {...props}></Icon>
<style>
:global(.dxdpz6gbz) {
  d: path("M17 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.it83nbbll) {
  d: path("M5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.ju0sk_7wf) {
  d: path("M2 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

:global(.ziznm1ama) {
  d: path("M14 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

</style>
