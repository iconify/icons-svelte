<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d0o8brb4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:notebook-shorthand" {...props}></Icon>
<style>
:global(.d0o8brb4d) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 4.5h14v17H5Zm3.5-2v4m3.5-4v4m3.5-4v4m-7.5 4h8m-8 4h8m-8 4h5");
}

</style>
