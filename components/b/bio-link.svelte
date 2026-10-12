<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kmg513bjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bio-link" {...props}></Icon>
<style>
:global(.kmg513bjk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 4.75h17.5M3.25 9h11M10 18.75H8a2.75 2.75 0 0 1 0-5.5h2m4 0h2a2.75 2.75 0 0 1 0 5.5h-2M9.5 16h5");
}

</style>
