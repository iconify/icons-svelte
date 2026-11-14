<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y8535qb9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:evacuation-order" {...props}></Icon>
<style>
:global(.y8535qb9l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14 6.5v-3H4v17h10v-3M8 12h12.5m-4-4l4 4l-4 4");
}

</style>
