<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x0jz_cigx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:hand-rest-cushion" {...props}></Icon>
<style>
:global(.x0jz_cigx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 7.5C8 6 16 6 20.5 7.5q1.5 3 0 6C16 15 8 15 3.5 13.5q-1.5-3 0-6m-1 10h19");
}

</style>
