<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rk8x_vp2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:heat-lightning" {...props}></Icon>
<style>
:global(.rk8x_vp2n) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21h19M14.25 3L9 11.5h6l-4.5 6.75m-7-.25a9 9 0 0 1 3.25-4.5m10.5 0A9 9 0 0 1 20.5 18");
}

</style>
