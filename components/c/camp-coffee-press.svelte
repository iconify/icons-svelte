<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eencprcuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:camp-coffee-press" {...props}></Icon>
<style>
:global(.eencprcuq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 7h11v14.5H5Zm11 3h1.5a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2H16M10.5 2.5v11M8 2.5h5m-5.25 11h5.5");
}

</style>
