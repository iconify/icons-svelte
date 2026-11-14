<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ls_wayrwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:blizzard" {...props}></Icon>
<style>
:global(.ls_wayrwk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14 3v14M8 6.5l12 7m-12 0l12-7M2.5 10H5m-2.5 7.5H10M6 21h11");
}

</style>
