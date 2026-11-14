<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="svo38jbaa"/><path class="vq2y_z06k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:mango-lassi" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.svo38jbaa) {
  d: path("m6.5 5l1 16h9l1-16M6.75 9h10.5");
}

:global(.vq2y_z06k) {
  d: path("m13.5 9l2-6.5H13");
}

</style>
