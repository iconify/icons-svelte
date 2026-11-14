<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pfb2_fbgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:avatar-add" {...props}></Icon>
<style>
:global(.pfb2_fbgw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 11.25a3.75 3.75 0 1 1 4.5 0c2.5 1 3.75 3.5 3.75 6.75v2a1 1 0 0 1-1 1h-10a1 1 0 0 1-1-1v-2c0-3.25 1.25-5.75 3.75-6.75Zm12.5-3.5v6m-3-3h6");
}

</style>
