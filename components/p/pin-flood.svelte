<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vkkwew_kt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pin-flood" {...props}></Icon>
<style>
:global(.vkkwew_kt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 7c1.75-2.25 4.25-2.25 6 0s4.25 2.25 6 0s4.25-2.25 6 0M3 13c1.75-2.25 4.25-2.25 6 0s4.25 2.25 6 0s4.25-2.25 6 0M3 19c1.75-2.25 4.25-2.25 6 0s4.25 2.25 6 0s4.25-2.25 6 0");
}

</style>
