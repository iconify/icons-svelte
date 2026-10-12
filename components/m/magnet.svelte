<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dibqajbur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:magnet" {...props}></Icon>
<style>
:global(.dibqajbur) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 2.75h4.5V13.5a2.75 2.75 0 0 0 5.5 0V2.75h4.5V13.5a7.25 7.25 0 0 1-14.5 0Zm0 4.5h4.5m5.5 0h4.5");
}

</style>
