<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qukh-45ey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:locker-room" {...props}></Icon>
<style>
:global(.qukh-45ey) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3h7v18h-7Zm10 0h7v18h-7ZM9 10.5V12m6-1.5V12M5.75 6.5h2.5m7.5 0h2.5");
}

</style>
