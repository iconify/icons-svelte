<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c7k4jfbvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:chart-export-sharp" {...props}></Icon>
<style>
:global(.c7k4jfbvp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 3.75H3.75v16.5h16.5V13m-12.5 3.25V13m3.75 3.25V11m3-1.5l6.75-6.75m-5.5 0h5.5v5.5");
}

</style>
