<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uf8kwx1ca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:rolling-pin-sharp" {...props}></Icon>
<style>
:global(.uf8kwx1ca) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 8h11.5v8H6.25zm3.5 0v8m4.5-8v8m-11.5-4h3.5m11.5 0h3.5");
}

</style>
