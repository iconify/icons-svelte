<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dtk8pv8kh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:air-pump" {...props}></Icon>
<style>
:global(.dtk8pv8kh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 3h10m-5 0v4.5m-.75 0h1.5a1.75 1.75 0 0 1 1.75 1.75v10A1.75 1.75 0 0 1 12.75 21h-1.5a1.75 1.75 0 0 1-1.75-1.75v-10a1.75 1.75 0 0 1 1.75-1.75M5 21h14");
}

</style>
