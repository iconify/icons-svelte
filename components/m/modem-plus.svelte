<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gno9empdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:modem-plus" {...props}></Icon>
<style>
:global(.gno9empdi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 8h5.75a3.5 3.5 0 0 1 3.5 3.5v.25a3.5 3.5 0 0 1-3.5 3.5H6a3.5 3.5 0 0 1-3.5-3.5v-.25A3.5 3.5 0 0 1 6 8m-.5 0V3m6.75 5V3M18 15v6m-3-3h6");
}

</style>
