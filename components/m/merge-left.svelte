<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a6sdxmycp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:merge-left" {...props}></Icon>
<style>
:global(.a6sdxmycp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14 21V3.5m-4 4l4-4l4 4M6.5 21v-3.5Q6.5 13 14 11");
}

</style>
