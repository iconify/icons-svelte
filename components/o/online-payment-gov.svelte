<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dsj6vsbcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:online-payment-gov" {...props}></Icon>
<style>
:global(.dsj6vsbcw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.3 15.5H4.5v-11h15v8.8m-2.2 2.2h-1.1m-13.7 3h8.8m3.45-.5l2 2L21 15.75");
}

</style>
