<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eo1w1_bkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:round-flask" {...props}></Icon>
<style>
:global(.eo1w1_bkr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 3v5.8a6.5 6.5 0 1 0 4 0V3M9 3h6M6.5 16h11");
}

</style>
