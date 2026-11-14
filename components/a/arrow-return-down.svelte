<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p6ojop6hs"/><path class="r-ih53m4g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:arrow-return-down" {...props}></Icon>
<style>
:global(.p6ojop6hs) {
  d: path("M5.5 15V9.5a4.5 4.5 0 0 1 9 0v10");
}

:global(.r-ih53m4g) {
  d: path("m10.5 15.5l4 4l4-4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
