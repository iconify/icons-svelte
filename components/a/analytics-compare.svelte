<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ytesqlrzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:analytics-compare" {...props}></Icon>
<style>
:global(.ytesqlrzs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5v19M3 20h6.25m-4.5 0v-8M8 20V7.5M14.75 20H21m-4.75 0V10m3.25 10v-6");
}

</style>
