<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d407e9rxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:interview-qa" {...props}></Icon>
<style>
:global(.d407e9rxa) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 8a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0M3 21.5c0-4 3-6.25 6.5-6.25S16 17.5 16 21.5m-.5-16A2.5 2.5 0 1 1 18 8v1.5m0 3h.01");
}

</style>
