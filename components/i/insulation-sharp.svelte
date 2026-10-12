<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b-ytf6xsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:insulation-sharp" {...props}></Icon>
<style>
:global(.b-ytf6xsf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h3.5v18.5h-3.5zm15 0h3.5v18.5h-3.5zM9.5 3.5l5 3l-5 3l5 3l-5 3l5 3l-5 2.25");
}

</style>
