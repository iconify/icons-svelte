<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dmt_sdbxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:barbell" {...props}></Icon>
<style>
:global(.dmt_sdbxc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 5h2.5v14H3Zm2.5 0H8v14H5.5ZM8 12h8m0-7h2.5v14H16Zm2.5 0H21v14h-2.5Z");
}

</style>
