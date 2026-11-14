<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ruod5db3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:arpeggio" {...props}></Icon>
<style>
:global(.ruod5db3g) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 3q2.5 2.25 0 4.5T7 12t0 4.5T7 21m5.25-16a2.75 1.75 0 1 0 5.5 0a2.75 1.75 0 1 0-5.5 0m0 7a2.75 1.75 0 1 0 5.5 0a2.75 1.75 0 1 0-5.5 0m0 7a2.75 1.75 0 1 0 5.5 0a2.75 1.75 0 1 0-5.5 0");
}

</style>
