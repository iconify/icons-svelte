<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p67i-xrde"/><path class="rh1seiq4v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:hydropower" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.p67i-xrde) {
  d: path("M5 9a6 6 0 1 0 12 0A6 6 0 1 0 5 9");
}

:global(.rh1seiq4v) {
  d: path("M11 9q-2.5-2.5 0-6m0 6q3.5-.25 5.25 3M11 9q-1 3.25-5.25 3m-3 7q1.75-1.5 3.5 0t3.5 0t3.5 0m6.25-4.5l-3.25 4h3.5l-2.5 3.25");
}

</style>
