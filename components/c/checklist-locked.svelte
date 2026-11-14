<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f1y0r1bet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:checklist-locked" {...props}></Icon>
<style>
:global(.f1y0r1bet) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 2.5h3.5V6H3Zm6.5 1.75H21M3 9h3.5v3.5H3Zm6.5 1.75h8M3 15.5h3.5V19H3v-3.5m6.5 1.75h2.7m2.8.25h6v4h-6Zm1.5 0v-1a1.5 1.5 0 0 1 3 0v1");
}

</style>
