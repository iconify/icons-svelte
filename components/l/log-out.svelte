<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l5tnlv_vq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:log-out" {...props}></Icon>
<style>
:global(.l5tnlv_vq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 4H6.5A2.5 2.5 0 0 0 4 6.5v11A2.5 2.5 0 0 0 6.5 20H10m-.5-8h11m-4-4l4 4l-4 4");
}

</style>
