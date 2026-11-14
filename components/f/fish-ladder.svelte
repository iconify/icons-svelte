<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wkm0a_b7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:fish-ladder" {...props}></Icon>
<style>
:global(.wkm0a_b7o) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21.5h6v-4h6v-4h7m-3-6.5C16 3 10.5 3 8 7L4.5 4v6L8 7c2.5 4 8 4 10.5 0m-4-.25h.01");
}

</style>
