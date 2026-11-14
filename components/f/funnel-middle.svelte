<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tffradcsh"/><path class="bsjrnvjup"/><path class="hnebgabqn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:funnel-middle" {...props}></Icon>
<style>
:global(.bsjrnvjup) {
  fill: currentColor;
  d: path("M7.5 10.25h9L13.75 14h-3.5Z");
}

:global(.hnebgabqn) {
  d: path("M10.25 16.75h3.5v4.5h-3.5Z");
}

:global(.tffradcsh) {
  d: path("M2.5 3.5h19l-3 4h-13Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
