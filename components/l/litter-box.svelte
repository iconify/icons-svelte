<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hcxxn3brv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:litter-box" {...props}></Icon>
<style>
:global(.hcxxn3brv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 10h19l-1.75 8H4.25ZM5 10c1-4 5.5-4.5 7.5 0");
}

</style>
