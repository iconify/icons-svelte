<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nsh11_bwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:canyon-view" {...props}></Icon>
<style>
:global(.nsh11_bwj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3.5H7v5h2V13h1.5v4h-8m19-13.5H17v5h-2V13h-1.5v4h8M4 20.5q2-1.5 4 0t4 0t4 0t4 0");
}

</style>
