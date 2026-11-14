<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nwhj4kbrz"/><path class="eynf50j7v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:robotics" {...props}></Icon>
<style>
:global(.eynf50j7v) {
  d: path("M7.5 13.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m6 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nwhj4kbrz) {
  d: path("M9.25 7.5h5.5A5.25 5.25 0 0 1 20 12.75v2.5a5.25 5.25 0 0 1-5.25 5.25h-5.5A5.25 5.25 0 0 1 4 15.25v-2.5A5.25 5.25 0 0 1 9.25 7.5m2.75-4v4");
}

</style>
