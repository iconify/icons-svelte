<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kpwgqrk-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:fan-speed-low" {...props}></Icon>
<style>
:global(.kpwgqrk-a) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 12a3.75 3.75 0 0 1 0-7a3.75 3.75 0 0 1 0 7a3.75 3.75 0 0 1 6 3.5a3.75 3.75 0 0 1-6-3.5a3.75 3.75 0 0 1-6 3.5a3.75 3.75 0 0 1 6-3.5Zm8.192-5.736a10 10 0 0 1 0 11.472");
}

</style>
