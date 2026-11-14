<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m442okpzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:keyboard" {...props}></Icon>
<style>
:global(.m442okpzr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2 6h20v12H2Zm4 3.75h.01m3.99 0h.01m3.99 0h.01m3.99 0h.01M6 14.25h.01m2.49 0h7m2.5 0h.01");
}

</style>
