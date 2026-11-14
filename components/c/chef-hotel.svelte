<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f-olsjbss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:chef-hotel" {...props}></Icon>
<style>
:global(.f-olsjbss) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 13.5V11A3.5 3.5 0 0 1 9 4.25a3.5 3.5 0 0 1 6 0A3.5 3.5 0 0 1 16.5 11v2.5Zm-1.5 8c0-2.5 2-4 3.5-4L12 20l2.5-2.5c1.5 0 3.5 1.5 3.5 4m-7.5-11v3m3-3v3");
}

</style>
