<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ztu8sy_fn"/><path class="ext23b30v"/><path class="zszj7qesl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cable-puller" {...props}></Icon>
<style>
:global(.ext23b30v) {
  d: path("M9.5 2.5H19V17a2.5 2.5 0 0 1-5 0v-1.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zszj7qesl) {
  d: path("M7.75 8a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

:global(.ztu8sy_fn) {
  d: path("M4 8a5.5 5.5 0 1 0 11 0A5.5 5.5 0 1 0 4 8");
}

</style>
