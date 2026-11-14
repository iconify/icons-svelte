<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ita0dsbvn"/><path class="ej99tzbnw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:rental-car" {...props}></Icon>
<style>
:global(.ej99tzbnw) {
  d: path("M5 18a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m11 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M5 11l2-4h5l1 4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ita0dsbvn) {
  d: path("M2.5 17v-6H13l3 3h5v3Z");
}

</style>
