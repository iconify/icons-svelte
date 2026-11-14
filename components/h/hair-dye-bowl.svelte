<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="msafvgbzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:hair-dye-bowl" {...props}></Icon>
<style>
:global(.msafvgbzk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 12h17a8.5 8.5 0 0 1-17 0m7 0l4.75-4.75m3.518-3.518za1.5 1.5 0 0 1 0 2.122l-1.414 1.414a1.5 1.5 0 0 1-2.122 0a1.5 1.5 0 0 1 0-2.122l1.414-1.414a1.5 1.5 0 0 1 2.122 0");
}

</style>
