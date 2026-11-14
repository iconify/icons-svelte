<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qwsdz3b8v"/><path class="k22izpe-i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:functional-group" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k22izpe-i) {
  d: path("M14 10a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-8 3.5l2 2m3 0l3.75-4");
}

:global(.qwsdz3b8v) {
  d: path("M2.5 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0m5 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m3.5-7a5 5 0 1 0 10 0a5 5 0 1 0-10 0");
}

</style>
