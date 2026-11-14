<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nzv9_g17j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:leaf-anatomy" {...props}></Icon>
<style>
:global(.nzv9_g17j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 19C3 10 10 3.5 20 4c.5 10-6 17-15 15Zm-2 2L16 8m-8 8h3m0-3v-3m3 0h2.5");
}

</style>
