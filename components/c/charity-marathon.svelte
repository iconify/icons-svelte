<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zig4kub2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:charity-marathon" {...props}></Icon>
<style>
:global(.zig4kub2n) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.16 16.5H3V5h5.5l2 3.5L15 10c3.764.941 5.979 1.439 6.227 3.162M3 13.5h11.2m3.8 7.75l-2.75-2.75A2 2 0 0 1 18 15.75a2 2 0 0 1 2.75 2.75Z");
}

</style>
