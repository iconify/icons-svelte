<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uf_gqut0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:playback-speed-sharp" {...props}></Icon>
<style>
:global(.uf_gqut0c) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.79 5.27l9.92 5.96L21 12l-1.29.77l-9.92 5.96l-1.29.77v-15zM2.75 8.25h3m-3 3.75h2m-2 3.75h3");
}

</style>
