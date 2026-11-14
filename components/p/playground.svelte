<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ocnle-bfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:playground" {...props}></Icon>
<style>
:global(.ocnle-bfu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 21.5V3m5 18.5V3m0 3.5c4.5 0 5.5 13 13 13m-18-10h5m-5 4h5m-5 4h5m-5-11h5");
}

</style>
