<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tkn_9lu9q"/><path class="q518x4bkb"/><path class="y7whs8brt"/><path class="tqn4jcb4f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:fridge-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.q518x4bkb) {
  d: path("M5 9h14");
}

:global(.tkn_9lu9q) {
  d: path("M5 4a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

:global(.tqn4jcb4f) {
  d: path("M8 11v3");
}

:global(.y7whs8brt) {
  d: path("M8 5v3");
}

</style>
