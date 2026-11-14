<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxdh0x62i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:light-tower" {...props}></Icon>
<style>
:global(.fxdh0x62i) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 3h10v5H5Zm5 5v9m-4.5 4.5L10 17l4.5 4.5M18 3.75l3-1m-3 4.5l3 1");
}

</style>
