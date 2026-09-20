<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="othqh9bcz"/><path class="z9ittvbis"/><path class="s9zlrxyyc"/><path class="ejc7sbawl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:laptop-outline-thin" {...props}></Icon>
<style>
:global(.ejc7sbawl) {
  d: path("M20 15v4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.othqh9bcz) {
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

:global(.s9zlrxyyc) {
  d: path("M4 15v4");
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

</style>
