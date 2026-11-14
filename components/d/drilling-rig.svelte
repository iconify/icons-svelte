<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-f9-_b_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:drilling-rig" {...props}></Icon>
<style>
:global(.t-f9-_b_y) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 17L10 3.5h4L18.5 17m-16 0h19m-13-9h7M7 12.5h10m-5 0V21");
}

</style>
