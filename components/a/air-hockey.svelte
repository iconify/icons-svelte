<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="efcev-o7b"/><path class="pfqgg1baf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:air-hockey" {...props}></Icon>
<style>
:global(.efcev-o7b) {
  d: path("M8 9.5a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0M2.5 18a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pfqgg1baf) {
  d: path("M12 9.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
