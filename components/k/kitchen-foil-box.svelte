<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nvevaebbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:kitchen-foil-box" {...props}></Icon>
<style>
:global(.nvevaebbx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 5h13.75A2.625 2.625 0 0 1 21.5 7.625v1.75A2.625 2.625 0 0 1 18.875 12H5.125A2.625 2.625 0 0 1 2.5 9.375v-1.75A2.625 2.625 0 0 1 5.125 5M2.5 8h19M6 12v5.5L8 19l2-1.5l2 1.5l2-1.5l2 1.5l2-1.5V12");
}

</style>
