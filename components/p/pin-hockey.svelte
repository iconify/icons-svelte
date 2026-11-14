<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bq1cycbqg"/><path class="rjr10ffwn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pin-hockey" {...props}></Icon>
<style>
:global(.bq1cycbqg) {
  d: path("M14 2.5L8.5 16h-4a1 1 0 0 0-1 1v1.5a1 1 0 0 0 1 1h6a1.5 1.5 0 0 0 1.5-1l5-16Zm1 14a3.25 1.75 0 1 0 6.5 0a3.25 1.75 0 1 0-6.5 0Z");
}

:global(.rjr10ffwn) {
  d: path("M15 16.5v2a3.25 1.75 0 0 0 6.5 0v-2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
