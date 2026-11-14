<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y4tgtpn0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:jammers" {...props}></Icon>
<style>
:global(.y4tgtpn0c) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 4h14l1 15h-6.5L12 10l-1.5 9H4Zm0 2.75h14");
}

</style>
