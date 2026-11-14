<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pc6ywjqim"/><path class="huf6y2b8y"/><path class="obdaw0b_v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:goal-scored" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.huf6y2b8y) {
  d: path("M5.25 20.5L6 8h12l.75 12.5");
}

:global(.obdaw0b_v) {
  d: path("M8.75 15.25a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0");
}

:global(.pc6ywjqim) {
  d: path("M2.5 20.5v-16h19v16");
}

</style>
