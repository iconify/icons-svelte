<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="v-nshmb6z"/><circle class="eaczzeban"/><path class="gsr9mu7_h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:grab-bar" {...props}></Icon>
<style>
:global(.eaczzeban) {
  cx: 19px;
  cy: 6.5px;
  r: 2.25px;
}

:global(.gsr9mu7_h) {
  d: path("M5 8.75v4a2.5 2.5 0 0 0 2.5 2.5h9a2.5 2.5 0 0 0 2.5-2.5v-4M2.75 21.25h18.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v-nshmb6z) {
  cx: 5px;
  cy: 6.5px;
  r: 2.25px;
}

</style>
