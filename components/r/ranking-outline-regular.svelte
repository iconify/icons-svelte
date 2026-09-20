<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ia46_gbxj"/><path class="btgfappwg"/><path class="i-zd2i_hi"/><path class="uxyzhxvwz"/><path class="rz_vrfdnw"/><path class="f8arnkt8y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ranking-outline-regular" {...props}></Icon>
<style>
:global(.btgfappwg) {
  d: path("M7 6h14");
}

:global(.f8arnkt8y) {
  d: path("M7 18h6");
}

:global(.i-zd2i_hi) {
  d: path("M3 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.ia46_gbxj) {
  d: path("M3 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rz_vrfdnw) {
  d: path("M3 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.uxyzhxvwz) {
  d: path("M7 12h10");
}

</style>
