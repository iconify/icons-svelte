<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="azlmfgbpz"/><path class="vrjexlb9w"/><path class="j6f47_hhv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:animal-shelter" {...props}></Icon>
<style>
:global(.azlmfgbpz) {
  d: path("M2.5 11L12 3.5l9.5 7.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j6f47_hhv) {
  d: path("M7.5 21v-6a4.5 4.5 0 0 1 9 0v6m-6.25-6.5h.01m3.49 0h.01m-1.76 3h.01");
}

:global(.vrjexlb9w) {
  d: path("M4.5 9.5V21h15V9.5");
}

</style>
