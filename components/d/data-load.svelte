<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lbs947byy"/><path class="hppncrbsz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:data-load" {...props}></Icon>
<style>
:global(.hppncrbsz) {
  d: path("M4 14c0 1.4 3.6 2.5 8 2.5s8-1.1 8-2.5M12 2.5V9M8.75 5.75L12 9l3.25-3.25");
}

:global(.lbs947byy) {
  d: path("M4 14c0-1.4 3.6-2.5 8-2.5s8 1.1 8 2.5v5c0 1.4-3.6 2.5-8 2.5S4 20.4 4 19Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
