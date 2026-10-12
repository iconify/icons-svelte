<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yr9f45buw"/><path class="pr0qow8yc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:crop" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pr0qow8yc) {
  d: path("M2.75 6.75h13.5a1 1 0 0 1 1 1v13.5");
}

:global(.yr9f45buw) {
  d: path("M6.75 2.75v13.5a1 1 0 0 0 1 1h13.5");
}

</style>
