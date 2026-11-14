<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xn5npbbjl"/><path class="fcspwobyd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:mint-julep" {...props}></Icon>
<style>
:global(.fcspwobyd) {
  d: path("M14 8.25q.5-5.75 6-5.75q-.5 5.5-6 5.75");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xn5npbbjl) {
  d: path("M6 10h12v9q0 2-2 2H8q-2 0-2-2Zm0 0q6-4 12 0");
}

</style>
