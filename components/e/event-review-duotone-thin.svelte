<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ybjj6ac-t"/><path class="cnjkjfbvs"/><path class="onn_u5lbx"/><path class="uto0n9pso"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:event-review-duotone-thin" {...props}></Icon>
<style>
:global(.cnjkjfbvs) {
  d: path("M3 5v14h18V5Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.onn_u5lbx) {
  d: path("m7 12 3 3 6 -6");
}

:global(.uto0n9pso) {
  d: path("M7 16h10");
}

:global(.ybjj6ac-t) {
  fill: currentColor;
  d: path("M3 5v14h18V5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
