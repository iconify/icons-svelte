<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ddikykb8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:audio-description" {...props}></Icon>
<style>
:global(.ddikykb8i) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 18L7 6l4 12m-6.5-4h5m4-8H15a6 6 0 0 1 0 12h-1.5Z");
}

</style>
