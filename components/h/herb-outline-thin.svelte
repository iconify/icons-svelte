<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mnwr0qhch"/><path class="hc0aulbwc"/><path class="fmqqksbgb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:herb-outline-thin" {...props}></Icon>
<style>
:global(.fmqqksbgb) {
  d: path("M12 14c4 0 6 -2 6 -5 -4 0 -6 2 -6 5");
}

:global(.hc0aulbwc) {
  d: path("M12 9C8 9 6 7 6 4c4 0 6 2 6 5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mnwr0qhch) {
  d: path("M12 4v17");
}

</style>
