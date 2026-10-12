<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x160ewbsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:clamp-sharp" {...props}></Icon>
<style>
:global(.x160ewbsh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 3h12v3.25h-10v9.5h10V19H5.25V3zm8.75 18.25v-10m-2.25 0h4.5m-4.75 10h5");
}

</style>
