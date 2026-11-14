<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r51gstb3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cell-borders" {...props}></Icon>
<style>
:global(.r51gstb3g) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 3.5h14A1.5 1.5 0 0 1 20.5 5v14a1.5 1.5 0 0 1-1.5 1.5H5A1.5 1.5 0 0 1 3.5 19V5A1.5 1.5 0 0 1 5 3.5m4.25 0v17m5.5-17v17M3.5 9.25h17m-17 5.5h17");
}

</style>
