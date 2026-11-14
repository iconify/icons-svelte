<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kiham4qtx"/><path class="hluir00hm"/><path class="gft6a_eiy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:hockey-goal-scored" {...props}></Icon>
<style>
:global(.gft6a_eiy) {
  d: path("M9 18a3 1.5 0 1 0 6 0a3 1.5 0 1 0-6 0");
}

:global(.hluir00hm) {
  d: path("M6.5 20L8 10h8l1.5 10");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kiham4qtx) {
  d: path("M3.5 20V7a2 2 0 0 1 2-2h13a2 2 0 0 1 2 2v13");
}

</style>
