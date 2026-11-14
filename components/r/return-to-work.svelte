<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cgiqhvrpl"/><path class="aefj23ssx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:return-to-work" {...props}></Icon>
<style>
:global(.aefj23ssx) {
  d: path("m8 10l2 2l2-2");
}

:global(.cgiqhvrpl) {
  d: path("M16.5 4.5zA2.5 2.5 0 0 1 19 7v2.5a2.5 2.5 0 0 1-2.5 2.5A2.5 2.5 0 0 1 14 9.5V7a2.5 2.5 0 0 1 2.5-2.5M13 14.75h7m-3.5 0v4.75m-3 0h6m-6 2.25h.01m5.99 0h.01M3 19.5v-11a3.5 3.5 0 0 1 7 0V12");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
