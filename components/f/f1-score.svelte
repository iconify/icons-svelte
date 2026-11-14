<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="op7ertb9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:f1-score" {...props}></Icon>
<style>
:global(.op7ertb9j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.5V20m-4.5 0h9M5.5 6h13m-16 7.5l3-7.5l3 7.5a3 3 0 0 1-6 0m13 0l3-7.5l3 7.5a3 3 0 0 1-6 0");
}

</style>
