<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l4ysi27mn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:exponent" {...props}></Icon>
<style>
:global(.l4ysi27mn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.75 9.25l8.75 11m0-11l-8.75 11m11.5-14.5c.25-1.25 1.25-2 2.5-2c1.5 0 2.5 1 2.5 2.25c0 1-.5 1.75-1.25 2.5L15.25 12h5");
}

</style>
