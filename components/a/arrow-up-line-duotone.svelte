<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yfsk7t85l"/><path class="az5a16bac"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-up-line-duotone" {...props}></Icon>
<style>
:global(.az5a16bac) {
  d: path("M18 10L12 4L6 10");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yfsk7t85l) {
  d: path("M12 20V4");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
