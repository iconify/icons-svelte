<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hv42-peji"/><path class="ih4y316fy"/><path class="mo52kbcea"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:asterisk-line-duotone" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hv42-peji) {
  d: path("M12 4V20");
}

:global(.ih4y316fy) {
  d: path("M5.07178 8L18.9282 16");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.mo52kbcea) {
  d: path("M5.07178 16L18.9282 8");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
