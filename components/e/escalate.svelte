<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b4q097o7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:escalate" {...props}></Icon>
<style>
:global(.b4q097o7t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.5H8V15h6V9.5h6.5M3.5 12L12 3.5m-4.25 0H12v4.25");
}

</style>
