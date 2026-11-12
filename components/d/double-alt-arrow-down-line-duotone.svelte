<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zen1fdcpk"/><path class="nhx5qezis"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:double-alt-arrow-down-line-duotone" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nhx5qezis) {
  d: path("M19 7L12 13L5 7");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.zen1fdcpk) {
  d: path("M19 11L12 17L5 11");
}

</style>
