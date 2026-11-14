<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jvg6zrbdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:priority-none" {...props}></Icon>
<style>
:global(.jvg6zrbdk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 21.5V8.9m2.4-5.4h11.1L16 8l2.5 4.5h-2.104m-7.8 0H5m-1.5-9l17 17");
}

</style>
