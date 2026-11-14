<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k7dbyrb5g"/><path class="sa4gg8hni"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:door-arched" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k7dbyrb5g) {
  d: path("M4 21.5V10a8 8 0 0 1 16 0v11.5");
}

:global(.sa4gg8hni) {
  d: path("M7 21.5v-11a5 5 0 0 1 10 0v11m-14.5 0h19m-7.5-6h.01");
}

</style>
