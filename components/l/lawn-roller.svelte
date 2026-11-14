<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eq9l0hy6h"/><path class="gfq49ypja"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:lawn-roller" {...props}></Icon>
<style>
:global(.eq9l0hy6h) {
  d: path("M15 11.5H6.5a2.5 4.5 0 0 0 0 9H15");
}

:global(.gfq49ypja) {
  d: path("M12.5 16a2.5 4.5 0 1 0 5 0a2.5 4.5 0 1 0-5 0m2.5-4.5l2.5-8m-1.5 0h4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
