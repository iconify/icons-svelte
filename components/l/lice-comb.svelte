<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xr-ja-z3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:lice-comb" {...props}></Icon>
<style>
:global(.xr-ja-z3n) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 4.5h14a2 2 0 0 1 2 2a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2a2 2 0 0 1 2-2m1 4v11m3-11v11m3-11v11m3-11v11m3-11v11");
}

</style>
