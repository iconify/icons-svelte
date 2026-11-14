<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-66skb7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:book-open-pages" {...props}></Icon>
<style>
:global(.w-66skb7t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 6.5c-2-1.5-4.75-2-9.5-2V18c4.75 0 7.5.5 9.5 2c2-1.5 4.75-2 9.5-2V4.5c-4.75 0-7.5.5-9.5 2m0 0V20M5 9l4.25.5M5 12.5l4.25.5m5.5-3.5L19 9m-4.25 4l4.25-.5");
}

</style>
