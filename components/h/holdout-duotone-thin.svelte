<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cvoep2bmy"/><path class="zrwkhybyf"/><path class="yih0nfb7c"/><path class="f8gsx7b5s"/><path class="e-07m9b9c"/><path class="dj91tzban"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:holdout-duotone-thin" {...props}></Icon>
<style>
:global(.cvoep2bmy) {
  fill: currentColor;
  d: path("M3 6a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.dj91tzban) {
  d: path("M6 17h8");
}

:global(.e-07m9b9c) {
  d: path("M6 11h12");
}

:global(.f8gsx7b5s) {
  d: path("M6 8h12");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yih0nfb7c) {
  d: path("M3 14h18");
}

:global(.zrwkhybyf) {
  d: path("M3 6a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

</style>
