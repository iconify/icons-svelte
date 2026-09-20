<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ewxguxn4h"/><path class="ipv0cebdm"/><path class="q3dplub_k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:event-reminder-outline-thin" {...props}></Icon>
<style>
:global(.ewxguxn4h) {
  d: path("M2 6h11v3l-2 2 2 2v3H2v-3l2 -2 -2 -2Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ipv0cebdm) {
  d: path("M13 16a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.q3dplub_k) {
  d: path("M17 16v-3");
}

</style>
