<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bfe4i6qcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:hair-damage" {...props}></Icon>
<style>
:global(.bfe4i6qcy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 2.5c2 4 2 8.5 1 12m0 0c-1 2.5-3.5 5-5.5 7m5.5-7c1 2.5 3.5 5 5.5 7");
}

</style>
