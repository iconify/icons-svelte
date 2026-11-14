<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e7j-t_b0r"/><path class="hze1ucbjj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:overhand-knot" {...props}></Icon>
<style>
:global(.e7j-t_b0r) {
  d: path("M2.5 18c5 0 10-1 13.25-4.5a5.5 5.5 0 1 0-7.5 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hze1ucbjj) {
  d: path("M8.25 13.5C11.5 17 16.5 18 21.5 18");
}

</style>
