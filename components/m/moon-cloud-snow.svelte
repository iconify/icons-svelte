<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jn31ms4nk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:moon-cloud-snow" {...props}></Icon>
<style>
:global(.jn31ms4nk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 16a3 3 0 0 1 0-6a4.5 4.5 0 0 1 8 1a2.5 2.5 0 0 1 1 5Zm14-13.5A3.5 3.5 0 1 0 21 8a3 3 0 0 1-1.5-5.5M6 19.5h.01m3.99 1h.01m3.99-1h.01");
}

</style>
