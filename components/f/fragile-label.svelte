<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l7ms0zbrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:fragile-label" {...props}></Icon>
<style>
:global(.l7ms0zbrd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 3.5h10c0 5.5-2 8-5 8S7 9 7 3.5m5 8V18m-4 2.5h8");
}

</style>
