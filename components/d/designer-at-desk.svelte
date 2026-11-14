<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mvll__erz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:designer-at-desk" {...props}></Icon>
<style>
:global(.mvll__erz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 9a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-1.5 9.5a4 4 0 0 1 8 0M12 8h9.5v7.5H12Zm4.75 7.5v3m-14.25 0h19");
}

</style>
