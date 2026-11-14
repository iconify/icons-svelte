<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="autnc1o3q"/><path class="wh6luetrn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:lodge" {...props}></Icon>
<style>
:global(.autnc1o3q) {
  d: path("M2.5 11.5L12 4l9.5 7.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wh6luetrn) {
  d: path("M5 10v10h14V10M5 13.5h14M5 16.75h14M16.5 3.5v4");
}

</style>
