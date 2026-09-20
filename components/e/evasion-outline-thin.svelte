<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ymp2b4b6u"/><path class="nfdm2s1cw"/><path class="zrubkobvc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:evasion-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nfdm2s1cw) {
  d: path("m5 3 16 16");
}

:global(.ymp2b4b6u) {
  d: path("M15 5h5v8l-8 8 -8 -8V5h5");
}

:global(.zrubkobvc) {
  d: path("M21 15v4h-4");
}

</style>
