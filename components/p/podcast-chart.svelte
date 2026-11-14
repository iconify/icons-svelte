<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zaaa3w60f"/><path class="n60-vhb8i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:podcast-chart" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n60-vhb8i) {
  d: path("M9.172 8.828a4 4 0 1 1 5.656 0");
}

:global(.zaaa3w60f) {
  d: path("M2.5 21v-5.5H8v-3.75h8v5.75h5.5V21Zm8.25-15a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

</style>
