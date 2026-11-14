<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a18pm1bpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ankle-support-wrap" {...props}></Icon>
<style>
:global(.a18pm1bpt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 2.5v13c0 2-1 3.5-1 5.5h13.5a2 2 0 0 0 0-4L14 16c-1-.5-2-1.5-2-3V2.5m-7.5 7l9 2m-9.5 2L14.5 16");
}

</style>
