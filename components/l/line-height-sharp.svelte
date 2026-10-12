<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n3gn00-fz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:line-height-sharp" {...props}></Icon>
<style>
:global(.n3gn00-fz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.25 6h9m-9 6h9m-9 6h9M6 4.25v15.5m-2.5-13L6 4.25l2.5 2.5m-5 10.5l2.5 2.5l2.5-2.5");
}

</style>
