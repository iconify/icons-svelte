<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ci7h_2bxp"/><path class="tr2mmnbmp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ai-label" {...props}></Icon>
<style>
:global(.ci7h_2bxp) {
  d: path("M8 5h11a2.5 2.5 0 0 1 2.5 2.5v9A2.5 2.5 0 0 1 19 19H8l-5.5-7Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.tr2mmnbmp) {
  d: path("M13.5 8q.5 3.5 4 4q-3.5.5-4 4q-.5-3.5-4-4q3.5-.5 4-4");
}

</style>
