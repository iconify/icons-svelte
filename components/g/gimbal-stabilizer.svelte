<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xzzacjwfo"/><path class="hb5k-yb4e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:gimbal-stabilizer" {...props}></Icon>
<style>
:global(.hb5k-yb4e) {
  d: path("M7.625 2.5h4.75A2.625 2.625 0 0 1 15 5.125v1.25A2.625 2.625 0 0 1 12.375 9h-4.75A2.625 2.625 0 0 1 5 6.375v-1.25A2.625 2.625 0 0 1 7.625 2.5M10 5.75h.01");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xzzacjwfo) {
  d: path("M12 13za2.5 2.5 0 0 1 2.5 2.5V19a2.5 2.5 0 0 1-2.5 2.5A2.5 2.5 0 0 1 9.5 19v-3.5A2.5 2.5 0 0 1 12 13m0 0v-1.5h6V5.75h-3");
}

</style>
