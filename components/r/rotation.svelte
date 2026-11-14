<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iktsbgbfm"/><path class="e-a7jvbtf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:rotation" {...props}></Icon>
<style>
:global(.e-a7jvbtf) {
  d: path("M17.25 11L16 8.5l2.5-1.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iktsbgbfm) {
  d: path("M12 2.5v19M4 12a8 4 0 0 0 16 0a8 4 0 0 0-4-3.5");
}

</style>
