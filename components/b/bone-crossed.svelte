<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="or-v_s8nl"/><path class="y4jee3bxr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bone-crossed" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.or-v_s8nl) {
  d: path("M8.75 7L17 15.25a1.75 1.75 0 1 1 .25 2a1.75 1.75 0 1 1-2-.25L7 8.75a1.75 1.75 0 1 1-.25-2a1.75 1.75 0 1 1 2 .25");
}

:global(.y4jee3bxr) {
  d: path("m15 10.75l2-2a1.75 1.75 0 1 0 .25-2a1.75 1.75 0 1 0-2 .25l-2 2M9 13.25l-2 2a1.75 1.75 0 1 0-.25 2a1.75 1.75 0 1 0 2-.25l2-2");
}

</style>
