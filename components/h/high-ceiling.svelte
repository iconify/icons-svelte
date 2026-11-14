<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wm3cirb_x"/><path class="dywmofmwe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:high-ceiling" {...props}></Icon>
<style>
:global(.dywmofmwe) {
  d: path("M8.75 14.5a3.25 3.25 0 0 1 6.5 0ZM12 16.75h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wm3cirb_x) {
  d: path("M2.5 21.5V10L12 2.5l9.5 7.5v11.5M12 2.5v8.75");
}

</style>
