<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="upqqzbb9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cheater-flag" {...props}></Icon>
<style>
:global(.upqqzbb9e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 2.5v19m0-18h14.5L16 7.75l2.367 4.025M16.762 12H4m14 2.5V18m0 3h.01");
}

</style>
