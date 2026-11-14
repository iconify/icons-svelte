<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x_nxc9bgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:printing-plate-x" {...props}></Icon>
<style>
:global(.x_nxc9bgn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 5h12a3.5 3.5 0 0 1 3.5 3.5v7A3.5 3.5 0 0 1 18 19H6a3.5 3.5 0 0 1-3.5-3.5v-7A3.5 3.5 0 0 1 6 5m3 4l6 6m0-6l-6 6M5.5 8.25h.01m12.99 0h.01");
}

</style>
