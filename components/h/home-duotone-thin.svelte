<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l_k_j9beu"/><path class="bhi4y-b3j"/><path class="a6e_o0bju"/><path class="xil7tiu3o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:home-duotone-thin" {...props}></Icon>
<style>
:global(.a6e_o0bju) {
  d: path("m3 11 9 -9 9 9");
}

:global(.bhi4y-b3j) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 11v9h12v-9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l_k_j9beu) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 11 9 -9 9 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xil7tiu3o) {
  d: path("M6 11v9h12v-9");
}

</style>
