<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vopf8xhqz"/><path class="l1mcfkbwi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:earth-sprout" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l1mcfkbwi) {
  d: path("M8.5 15a3.5 7 0 1 0 7 0a3.5 7 0 1 0-7 0M5 15h14m-7-7V5.5m0 0q.75-3 4.5-3q-.75 3-4.5 3m0 0q-.75-3-4.5-3q.75 3 4.5 3");
}

:global(.vopf8xhqz) {
  d: path("M5 15a7 7 0 1 0 14 0a7 7 0 1 0-14 0");
}

</style>
