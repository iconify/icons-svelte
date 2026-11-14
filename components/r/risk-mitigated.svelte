<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ls5f2mbey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:risk-mitigated" {...props}></Icon>
<style>
:global(.ls5f2mbey) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.539 19H2.5L12 2.5l5.289 9.186M12 8.5v4m0 3h.01m5.99-1v7m-3-3l3 3l3-3");
}

</style>
