<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n_i7jf3cu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chart-candlestick-round" {...props}></Icon>
<style>
:global(.n_i7jf3cu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 17a2 2 0 1 1 4 0v1a2 2 0 1 1-4 0Zm7-10a2 2 0 1 1 4 0v3a2 2 0 1 1-4 0Zm7 10a2 2 0 1 1 4 0a2 2 0 0 1-4 0M5 12v3m0 5v1m7-18v2m0 7v3m7-3v3m0 4v2");
}

</style>
