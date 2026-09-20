<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ler50rfbf"/><path class="b-i6_ubyt"/><path class="uerippblb"/><path class="i4kf51esh"/><path class="iwg_dsj0c"/><path class="m0f5ny81l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:plant-grow-outline-thin" {...props}></Icon>
<style>
:global(.b-i6_ubyt) {
  d: path("M3 14c0 -3.6 2.4 -6 6 -6 0 3.6 -2.4 6 -6 6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i4kf51esh) {
  d: path("M19 5v14");
}

:global(.iwg_dsj0c) {
  d: path("M16.5 7.5 19 5l2.5 2.5");
}

:global(.ler50rfbf) {
  d: path("M9 8v12");
}

:global(.m0f5ny81l) {
  d: path("M5 20h8");
}

:global(.uerippblb) {
  d: path("M10 11c0 -3.6 2.4 -6 6 -6 0 3.6 -2.4 6 -6 6");
}

</style>
