<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zdzk-qd3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:refrigerant-gauge" {...props}></Icon>
<style>
:global(.zdzk-qd3j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 10a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0M7 17l-3 4m13-4l3 4m-8-11l3-3m-3 3h.01");
}

</style>
