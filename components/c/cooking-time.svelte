<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lbcyuebib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cooking-time" {...props}></Icon>
<style>
:global(.lbcyuebib) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 13a8 8 0 1 0 16 0a8 8 0 1 0-16 0m8 0V9m0 4l3 1.5m-5.5-11h5");
}

</style>
