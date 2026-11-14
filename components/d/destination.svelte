<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wwhkkbb2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:destination" {...props}></Icon>
<style>
:global(.wwhkkbb2m) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16 14s-4.5-3.5-4.5-6.5a4.5 4.5 0 0 1 9 0c0 3-4.5 6.5-4.5 6.5m0-6.5h.01M4 20h.01M8 18.5h.01M12 17h.01");
}

</style>
