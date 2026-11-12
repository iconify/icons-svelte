<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hqmot3fke"/><path class="b-y5if5uj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:equal-line-duotone" {...props}></Icon>
<style>
:global(.b-y5if5uj) {
  d: path("M4 15H20");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hqmot3fke) {
  d: path("M4 9H20");
}

</style>
