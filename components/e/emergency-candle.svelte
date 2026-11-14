<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-oys5b-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:emergency-candle" {...props}></Icon>
<style>
:global(.t-oys5b-s) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 12h3.5a1.75 1.75 0 0 1 1.75 1.75v6a1.75 1.75 0 0 1-1.75 1.75h-3.5a1.75 1.75 0 0 1-1.75-1.75v-6A1.75 1.75 0 0 1 10.25 12M12 12V9.25m0-7c1.75 2 2.5 3.25 2.5 4.5a2.5 2.5 0 0 1-5 0c0-1.25.75-2.5 2.5-4.5");
}

</style>
