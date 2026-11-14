<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bnqy4obot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:grain-pile" {...props}></Icon>
<style>
:global(.bnqy4obot) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 18.5C7 14 9.5 6 12 6s5 8 9 12.5m-18.5 0h19M12 11h.01M10 14.5h.01m3.99 0h.01");
}

</style>
