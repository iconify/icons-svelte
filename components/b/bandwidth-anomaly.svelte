<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="km2caxd_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bandwidth-anomaly" {...props}></Icon>
<style>
:global(.km2caxd_j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 16H6l1.5-2.5L9 16h1.5l2-12l2 12H16l1.5-2.5L19 16h2.5m-19 4.5h19");
}

</style>
