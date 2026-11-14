<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ykixl0bmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:invoice-subtotal" {...props}></Icon>
<style>
:global(.ykixl0bmn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 2.5h14V21l-2.25-1.5L14.5 21L12 19.5L9.5 21l-2.25-1.5L5 21Zm3.5 4h7m-7 5h7m-3.5 4h3.5");
}

</style>
