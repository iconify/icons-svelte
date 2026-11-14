<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="irn215s9b"/><path class="twdl6n0hv"/><path class="v-l-oli1j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:repo-watch" {...props}></Icon>
<style>
:global(.irn215s9b) {
  d: path("m5 3.5l15 4l-1.25 5l-15-4Z");
}

:global(.twdl6n0hv) {
  fill: currentColor;
  d: path("M14.25 9a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v-l-oli1j) {
  d: path("M4 12.5v8M4 16h7.25v-5.5");
}

</style>
