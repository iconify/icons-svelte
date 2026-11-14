<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="afox1hb2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:policy-booklet" {...props}></Icon>
<style>
:global(.afox1hb2w) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 3h11.5v18H4Zm11.5 2l4 1.25v13.5l-4 1.25M7 7.5h5.5m-5.5 4h3.5");
}

</style>
