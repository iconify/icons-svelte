<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nhg1iwb_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:map-cluster" {...props}></Icon>
<style>
:global(.nhg1iwb_w) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 11.5c-1.75-2-3.5-3.75-3.5-5.5a3.5 3.5 0 0 1 7 0c0 1.75-1.75 3.5-3.5 5.5M7 21c-1.75-2-3.5-3.75-3.5-5.5a3.5 3.5 0 0 1 7 0c0 1.75-1.75 3.5-3.5 5.5m10 0c-1.75-2-3.5-3.75-3.5-5.5a3.5 3.5 0 0 1 7 0c0 1.75-1.75 3.5-3.5 5.5");
}

</style>
