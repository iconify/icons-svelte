<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lwzjgbcnp"/><path class="aw-hu8o0p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:incident-chat" {...props}></Icon>
<style>
:global(.aw-hu8o0p) {
  d: path("m13.49 7.922l2.869 4.661a1.75 1.75 0 0 1-1.491 2.667H9.132a1.75 1.75 0 0 1-1.491-2.667l2.869-4.661a1.75 1.75 0 0 1 2.98 0M12 9v2.25m0 2h.01");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lwzjgbcnp) {
  d: path("M4.5 2.5h15a2 2 0 0 1 2 2V16a2 2 0 0 1-2 2H10l-4.5 3.5V18h-1a2 2 0 0 1-2-2V4.5a2 2 0 0 1 2-2");
}

</style>
