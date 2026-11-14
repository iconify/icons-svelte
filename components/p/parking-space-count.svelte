<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dfryx5b8t"/><path class="ngr8pmbps"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:parking-space-count" {...props}></Icon>
<style>
:global(.dfryx5b8t) {
  d: path("M6 3h12a3.5 3.5 0 0 1 3.5 3.5v6A3.5 3.5 0 0 1 18 16H6a3.5 3.5 0 0 1-3.5-3.5v-6A3.5 3.5 0 0 1 6 3m6 13v5.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ngr8pmbps) {
  d: path("M6 13V6h2a2 2 0 0 1 0 4H6m7-3.5V13m2.5-5.25a1.75 1.75 0 0 1 3.5 0c0 2-3.5 3-3.5 5.25H19");
}

</style>
