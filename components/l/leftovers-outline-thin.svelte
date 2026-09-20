<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ydwr2p6jl"/><path class="x50q_4bdr"/><path class="mhnr27bap"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:leftovers-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mhnr27bap) {
  d: path("M12 7v3");
}

:global(.x50q_4bdr) {
  d: path("M3 10h18");
}

:global(.ydwr2p6jl) {
  d: path("M5 13v7h14v-7Z");
}

</style>
