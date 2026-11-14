<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="arcyxdx5y"/><path class="lxtaqtb6z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cell-division" {...props}></Icon>
<style>
:global(.arcyxdx5y) {
  d: path("M12 9.25C10.75 7 9 6 7 6c-2.75 0-4.5 2.75-4.5 6s1.75 6 4.5 6c2 0 3.75-1 5-3.25C13.25 17 15 18 17 18c2.75 0 4.5-2.75 4.5-6S19.75 6 17 6c-2 0-3.75 1-5 3.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lxtaqtb6z) {
  d: path("M5 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
