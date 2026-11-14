<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y_u521utk"/><path class="lwjjo7bmh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:room-service-tray" {...props}></Icon>
<style>
:global(.lwjjo7bmh) {
  d: path("M10.25 6.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y_u521utk) {
  d: path("M3.5 16.5a8.5 8.5 0 0 1 17 0m-18 0h19l-1.5 3H4Z");
}

</style>
