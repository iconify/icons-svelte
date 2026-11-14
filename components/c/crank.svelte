<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kjfk81btm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:crank" {...props}></Icon>
<style>
:global(.kjfk81btm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14.25a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0Zm6.5 0l8.5-7.5m-.5-1.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-8 9h.01");
}

</style>
