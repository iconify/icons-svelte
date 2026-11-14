<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ten78rush"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:layout-grid-add" {...props}></Icon>
<style>
:global(.ten78rush) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5h5v5h-5Zm7.75 0h5v5h-5ZM2.5 10.25h5v5h-5Zm9.65 5h-1.9v-5h5v1.9M18 15v6m-3-3h6");
}

</style>
