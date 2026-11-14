<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sh46e33-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:link-off" {...props}></Icon>
<style>
:global(.sh46e33-n) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 16.5a4.5 4.5 0 0 1-2.645-8.141M7.5 16.5H9m7.5-9a4.5 4.5 0 0 1 2.645 8.141M15 7.5h1.5m-13-4l17 17");
}

</style>
