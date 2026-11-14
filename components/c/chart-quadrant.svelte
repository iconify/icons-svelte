<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rtdolpbfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chart-quadrant" {...props}></Icon>
<style>
:global(.rtdolpbfb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.875 3.5h8.25A4.375 4.375 0 0 1 20.5 7.875v8.25a4.375 4.375 0 0 1-4.375 4.375h-8.25A4.375 4.375 0 0 1 3.5 16.125v-8.25A4.375 4.375 0 0 1 7.875 3.5M12 3.5v17M3.5 12h17m-13-4.5h.01M17 7h.01m-.51 9.5h.01");
}

</style>
