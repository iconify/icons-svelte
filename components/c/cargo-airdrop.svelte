<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hgwz30btp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cargo-airdrop" {...props}></Icon>
<style>
:global(.hgwz30btp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 11c0-4.5 3-7.5 7-7.5s7 3 7 7.5Zm4.5 5h5v5h-5Zm-4-5l4 5m9-5l-4 5");
}

</style>
