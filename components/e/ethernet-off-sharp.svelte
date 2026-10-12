<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ty42il_vb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:ethernet-off-sharp" {...props}></Icon>
<style>
:global(.ty42il_vb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 4.75h16V16H15.5v3.75h-7V16H3.25V4.75zm2.75 3.5v3m3-3v3m3-3v3m3-3v3");
}

</style>
