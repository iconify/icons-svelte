<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l97qxpbxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bobby-pin" {...props}></Icon>
<style>
:global(.l97qxpbxz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 21.5V6a3.5 3.5 0 0 1 7 0m0 0v2.5l1.75 2l-1.75 2l1.75 2l-1.75 2v5");
}

</style>
