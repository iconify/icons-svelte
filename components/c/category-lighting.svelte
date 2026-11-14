<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lubjufb1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:category-lighting" {...props}></Icon>
<style>
:global(.lubjufb1c) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3a6 6 0 0 1 4 10.5V16H8v-2.5A6 6 0 0 1 12 3M9.5 19h5m-4 2.5h3");
}

</style>
