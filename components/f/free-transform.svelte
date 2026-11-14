<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jwe07xb3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:free-transform" {...props}></Icon>
<style>
:global(.jwe07xb3w) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 3.25h3.5v3.5h-3.5Zm14 0h3.5v3.5h-3.5Zm0 14h3.5v3.5h-3.5Zm-14 0h3.5v3.5h-3.5ZM6.75 5h10.5M6.75 19h10.5M5 6.75v10.5m14-10.5v10.5M9.5 9.5l5 5m-5-2v-3h3m-1 5h3v-3");
}

</style>
