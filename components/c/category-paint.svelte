<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h7qxi4vgc"/><path class="trm8uhbia"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:category-paint" {...props}></Icon>
<style>
:global(.h7qxi4vgc) {
  d: path("M6.625 3.5h10.75A2.625 2.625 0 0 1 20 6.125v.75A2.625 2.625 0 0 1 17.375 9.5H6.625A2.625 2.625 0 0 1 4 6.875v-.75A2.625 2.625 0 0 1 6.625 3.5M12 9.5v4m0 0h-2V21h4v-7.5z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.trm8uhbia) {
  d: path("M20 6.5V12h-8");
}

</style>
