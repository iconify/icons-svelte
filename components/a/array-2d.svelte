<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iay_pst3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:array-2d" {...props}></Icon>
<style>
:global(.iay_pst3l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 2.5h-2v19h2m15-19h2v19h-2M5.25 5.25h5.25v5.25H5.25Zm8.25 0h5.25v5.25H13.5ZM5.25 13.5h5.25v5.25H5.25Zm8.25 0h5.25v5.25H13.5Z");
}

</style>
