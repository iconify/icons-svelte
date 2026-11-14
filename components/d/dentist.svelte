<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qo6s1mbjv"/><path class="liug_b8-q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:dentist" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.liug_b8-q) {
  d: path("M9 6a3 3 0 1 0 6 0a3 3 0 1 0-6 0M4 21.5c0-2 3.5-3.25 8-3.25s8 1.25 8 3.25M12 6h.01");
}

:global(.qo6s1mbjv) {
  d: path("M9 6H7v4.5a5 5 0 0 0 10 0V6h-2");
}

</style>
