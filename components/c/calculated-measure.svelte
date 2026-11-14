<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xu4upibtu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:calculated-measure" {...props}></Icon>
<style>
:global(.xu4upibtu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 5H4l4 7l-4 7h7m6.5-13.5v5M15 8h5m-5 6.5h5m-5 3h5");
}

</style>
