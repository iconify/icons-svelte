<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ma2_qns7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:apron-feeder" {...props}></Icon>
<style>
:global(.ma2_qns7h) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 2.5l3.5 6h4l3.5-6M3.842 10.637l17.855 6.498l-1.539 4.228l-17.855-6.498Zm4.699 1.71l-1.539 4.228m5.768-2.689l-1.54 4.228m5.768-2.689l-1.539 4.228");
}

</style>
