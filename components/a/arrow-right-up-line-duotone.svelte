<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ygpzi6bzb"/><path class="lzc0iw4ot"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-right-up-line-duotone" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lzc0iw4ot) {
  d: path("M9 6H18V15");
}

:global(.ygpzi6bzb) {
  d: path("M6 18L18 6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
