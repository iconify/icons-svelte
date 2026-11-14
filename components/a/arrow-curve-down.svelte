<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fdau0149r"/><path class="koyj9mdsb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:arrow-curve-down" {...props}></Icon>
<style>
:global(.fdau0149r) {
  d: path("M4 5.5c7.5 0 12 5 12 13.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.koyj9mdsb) {
  d: path("M12.5 15.5L16 19l3.5-3.5");
}

</style>
