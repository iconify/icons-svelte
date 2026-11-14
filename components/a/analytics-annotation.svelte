<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dz_2cac_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:analytics-annotation" {...props}></Icon>
<style>
:global(.dz_2cac_i) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 13v8m4-17v17m4-12v12m4-7.5h5a1 1 0 0 1 1 1V18a1 1 0 0 1-1 1H18l-2.5 2v-2a1 1 0 0 1-1-1v-3.5a1 1 0 0 1 1-1");
}

</style>
