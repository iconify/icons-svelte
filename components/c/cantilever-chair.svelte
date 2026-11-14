<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ky93dn4hi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cantilever-chair" {...props}></Icon>
<style>
:global(.ky93dn4hi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 2.5V12a1.5 1.5 0 0 0 1.5 1.5h6.5a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2H6m5-10.75h6");
}

</style>
