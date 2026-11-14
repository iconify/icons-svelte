<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-k2skbzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pin-walk" {...props}></Icon>
<style>
:global(.t-k2skbzu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.5 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0M13 9.25L11 15m-3.5 6.5L11 15l3 3l1 3.5m-6.5-8l1.5-3.25l2.75-.5L16.5 13");
}

</style>
