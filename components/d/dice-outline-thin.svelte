<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nzpsuduik"/><path class="tcxfk34nj"/><path class="i_15ylggi"/><path class="sktrp_58r"/><path class="pyew6cbwi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dice-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i_15ylggi) {
  d: path("M15 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nzpsuduik) {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.pyew6cbwi) {
  d: path("M15 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.sktrp_58r) {
  d: path("M7 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.tcxfk34nj) {
  d: path("M7 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
