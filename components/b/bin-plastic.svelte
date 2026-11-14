<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fr7h0jopz"/><path class="caaa9kgvp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bin-plastic" {...props}></Icon>
<style>
:global(.caaa9kgvp) {
  d: path("M11 8.5h2v2l1.5 2V18h-5v-5.5l1.5-2Z");
}

:global(.fr7h0jopz) {
  d: path("M3.5 5.5h17m-11 0v-2h5v2M5 5.5L6.5 21h11L19 5.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
