<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d5g7s7bph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:graduated-cylinder-sharp" {...props}></Icon>
<style>
:global(.d5g7s7bph) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 4.25v-1.5h7.5V18.5h-7.5Zm0 3h3.5m-3.5 3.5h2.25m-2.25 3.5h3.5m-6 4.25h12.5v2.75H5.75z");
}

</style>
