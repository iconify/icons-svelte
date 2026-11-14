<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c53n_cbfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:dental-syringe" {...props}></Icon>
<style>
:global(.c53n_cbfb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.152 5.77l4.949 4.95l-7.071 7.071l-4.949-4.95Zm-1.768-1.768l8.485 8.485m-1.414-7.071l-2.828 2.829m.707-4.95l4.242 4.243M8.555 15.316l-5.303 5.303");
}

</style>
