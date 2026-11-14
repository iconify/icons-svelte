<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sfvettglk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:balloon-glass" {...props}></Icon>
<style>
:global(.sfvettglk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 3c-4.5 4.5-3.5 12.5 4 12.5s8.5-8 4-12.5Zm4 12.5v5m-4 0h8");
}

</style>
