<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j26utkbsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:arrows-in" {...props}></Icon>
<style>
:global(.j26utkbsq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12h.01M3.5 3.5L9 9m0-3.5V9H5.5m15-5.5L15 9m3.5 0H15V5.5m5.5 15L15 15m0 3.5V15h3.5m-15 5.5L9 15m-3.5 0H9v3.5");
}

</style>
