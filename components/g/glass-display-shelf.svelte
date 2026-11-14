<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bpnvgkbwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:glass-display-shelf" {...props}></Icon>
<style>
:global(.bpnvgkbwy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14h19m-18 0v5.5L7 14m13.5 0v5.5L17 14m-7.25 0C7 11.5 7.5 8 10 6.5v-2h4v2c2.5 1.5 3 5 .25 7.5");
}

</style>
