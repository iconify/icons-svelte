<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="vo6pq_eni"/><path class="wo8rm3bwm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-collapse-line-duotone" {...props}></Icon>
<style>
:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vo6pq_eni) {
  d: path("M21 6H13M21 10H13M21 14H13M21 18H13");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.wo8rm3bwm) {
  stroke-linejoin: round;
  d: path("M5.28516 18L6.99944 16L5.28516 14M5.28516 10L6.99944 8L5.28516 6");
}

</style>
