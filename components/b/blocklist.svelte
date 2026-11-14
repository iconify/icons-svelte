<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_4qc5pts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:blocklist" {...props}></Icon>
<style>
:global(.i_4qc5pts) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.5 4.5l4 4m0-4l-4 4m7.5-2h9.5m-17 4l4 4m0-4l-4 4m7.5-2h9.5m-17 4l4 4m0-4l-4 4m7.5-2h9.5");
}

</style>
