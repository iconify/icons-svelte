<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qnkt1qvay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:recenter-view" {...props}></Icon>
<style>
:global(.qnkt1qvay) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 12a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0M12 2.5V8m0 8v5.5M2.5 12H8m8 0h5.5M12 12h.01");
}

</style>
