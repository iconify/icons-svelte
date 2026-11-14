<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fcn10p8ye"/><path class="xfqpozbou"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:lane-change-left" {...props}></Icon>
<style>
:global(.fcn10p8ye) {
  d: path("M2.5 2.5v19m19-19v19M12 2.5v4m0 11v4m4 0V16c0-4-8-4-8-8V4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xfqpozbou) {
  d: path("M5.25 6.75L8 4l2.75 2.75");
}

</style>
