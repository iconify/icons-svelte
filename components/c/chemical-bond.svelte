<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b0rkrsv1g"/><path class="hzt_w3bcs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chemical-bond" {...props}></Icon>
<style>
:global(.b0rkrsv1g) {
  fill: currentColor;
  d: path("M2.75 15.5a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0m11-7a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hzt_w3bcs) {
  d: path("m9.75 13.5l4.5-3");
}

</style>
