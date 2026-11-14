<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mpuhvmpgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:hourglass-plus" {...props}></Icon>
<style>
:global(.mpuhvmpgl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 3h8v2c0 2.5-2 5-4 7c2 2 4 4.5 4 7v2H5v-2c0-2.5 2-5 4-7c-2-2-4-4.5-4-7ZM3.5 3h11m-11 18h11m4-12v6m-3-3h6");
}

</style>
