<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eqeq-vbmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ferry-terminal" {...props}></Icon>
<style>
:global(.eqeq-vbmf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 3.5h9V9H7ZM2.5 9h19L19 14H5Zm.5 8.5q2.25-1.5 4.5 0t4.5 0t4.5 0t4.5 0M3 20.75q2.25-1.5 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
