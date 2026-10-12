<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kqjegbcgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:frame-plus-sharp" {...props}></Icon>
<style>
:global(.kqjegbcgw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 3.75v16.5m9.5-16.5v16.5m-13-13h16.5m-16.5 9.5h16.5M10 10h4v4h-4z");
}

</style>
