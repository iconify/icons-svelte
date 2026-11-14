<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lya9_m8tb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:lead-nurture" {...props}></Icon>
<style>
:global(.lya9_m8tb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21V11M7 21h10m-5-8c0-3.5-2.5-6-7-6c0 3.5 2.5 6 7 6m0-2c0-4.5 3-7 8-7c0 4.5-3 7-8 7");
}

</style>
