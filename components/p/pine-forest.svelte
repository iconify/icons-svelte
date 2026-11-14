<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zz9abmmrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pine-forest" {...props}></Icon>
<style>
:global(.zz9abmmrp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 21v-4m0 0H3.5L7 9l3.5 8Zm10 4v-7m0 0h-4.5L17 5l4.5 9Z");
}

</style>
