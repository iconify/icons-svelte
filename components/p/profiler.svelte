<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="boemvuscg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:profiler" {...props}></Icon>
<style>
:global(.boemvuscg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 16.75h19v4h-19Zm0-6.75h11v4h-11Zm13.75 0h5.25v4h-5.25Zm-11-6.75h6v4h-6Z");
}

</style>
