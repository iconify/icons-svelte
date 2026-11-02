<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="l1txs0sri"/><path class="iy2wc_bgp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:golf-duocolor" {...props}></Icon>
<style>
:global(.iy2wc_bgp) {
  d: path("M10 11V5c0-.919 1.081-1.46 2-1l4 2a1.118 1.118 0 0 1 0 2zm0 0v6");
}

:global(.l1txs0sri) {
  stroke-opacity: 0.4;
  d: path("M6 19c0 1.105 1.79 2 4 2s4-.895 4-2");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
