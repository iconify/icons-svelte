<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u_3x_vtgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:chart-waffle" {...props}></Icon>
<style>
:global(.u_3x_vtgc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3.5h4v4h-4Zm6.5 0h4v4h-4Zm6.5 0h4v4h-4ZM3.5 10h4v4h-4Zm6.5 0h4v4h-4Zm6.5 0h4v4h-4Zm-13 6.5h4v4h-4Zm6.5 0h4v4h-4Zm6.5 0h4v4h-4Z");
}

</style>
