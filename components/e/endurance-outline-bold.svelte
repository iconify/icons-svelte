<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="cmt-chbtl"/><path class="iwanrcb5f"/><path class="s97tcsbyl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:endurance-outline-bold" {...props}></Icon>
<style>
:global(.cmt-chbtl) {
  d: path("m2 20 6 -6 3 3 4 -4 7 7");
}

:global(.iwanrcb5f) {
  d: path("M15 13V5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.s97tcsbyl) {
  d: path("M15 5h4v4h-4");
}

</style>
