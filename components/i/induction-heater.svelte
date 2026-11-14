<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x1tjxz-vn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:induction-heater" {...props}></Icon>
<style>
:global(.x1tjxz-vn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 12a1.5 5.5 0 1 0 3 0a1.5 5.5 0 1 0-3 0m5 0a1.5 5.5 0 1 0 3 0a1.5 5.5 0 1 0-3 0m5 0a1.5 5.5 0 1 0 3 0a1.5 5.5 0 1 0-3 0m-13 0h19");
}

</style>
