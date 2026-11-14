<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="got5039yq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:dead-reckoning" {...props}></Icon>
<style>
:global(.got5039yq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 20.5h.01M7 17h.01m3.49-3.5h.01M10 10.75h3.25V14m1.25-7.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
