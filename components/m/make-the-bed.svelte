<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="df9miabit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:make-the-bed" {...props}></Icon>
<style>
:global(.df9miabit) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 5v15m0-7.5h15.5A2.5 2.5 0 0 1 21 15v5M3 16.5h18m-15.5-8h5V11h-5Zm8-2l2 2l4-4.5");
}

</style>
