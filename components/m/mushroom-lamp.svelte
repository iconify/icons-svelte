<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vjg0o9bca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:mushroom-lamp" {...props}></Icon>
<style>
:global(.vjg0o9bca) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 11a8.5 8.5 0 0 1 17 0Zm8.5 0v7m-5.5 3a5.5 3 0 0 1 11 0Z");
}

</style>
