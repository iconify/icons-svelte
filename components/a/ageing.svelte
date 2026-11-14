<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xkzwx9bqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ageing" {...props}></Icon>
<style>
:global(.xkzwx9bqx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.75 5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M11 9.25C9 10.5 8.25 12.5 8.5 15L7 21.5M8.5 15l2.5 6.5M10.25 10L14 13.5m0 0a1.75 1.75 0 0 1 3.5 0v8");
}

</style>
