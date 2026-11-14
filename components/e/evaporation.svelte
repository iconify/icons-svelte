<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ab4ny6j-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:evaporation" {...props}></Icon>
<style>
:global(.ab4ny6j-w) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 15.5h18c0 3.5-3.5 5.5-9 5.5s-9-2-9-5.5m4.5-3q-1.875-2.25 0-4.5t0-4.5m4.5 9q-1.875-2.25 0-4.5t0-4.5m4.5 9q-1.875-2.25 0-4.5t0-4.5");
}

</style>
