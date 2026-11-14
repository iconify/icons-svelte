<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ycjznbcns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:crop-top" {...props}></Icon>
<style>
:global(.ycjznbcns) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 5h2.5c0 5.5 7 5.5 7 0H18c0 3.5 1.5 5.5 2 6.5V19H4v-7.5c.5-1 2-3 2-6.5M4 16h16");
}

</style>
