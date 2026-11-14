<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r2w72tz-y"/><path class="qfv0rmi_j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:microfiber-cloth" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qfv0rmi_j) {
  d: path("M21 13q-1 5.5-8 8");
}

:global(.r2w72tz-y) {
  d: path("M5 3h14a2 2 0 0 1 2 2v8q-5 0-8 8H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2");
}

</style>
