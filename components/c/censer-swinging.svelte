<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dis23rv8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:censer-swinging" {...props}></Icon>
<style>
:global(.dis23rv8d) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 13h14a7 7 0 0 1-14 0M6.5 3h7m-7 0L5 13m8.5-10L15 13M10 3v10m9.5-1.5c-1.5-2 1.5-3.5 0-6");
}

</style>
