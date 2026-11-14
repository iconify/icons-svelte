<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kr71oacge"/><path class="xu68j4rdt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:event-loop" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kr71oacge) {
  d: path("M20 12.5a8 8 0 1 1-8-8");
}

:global(.xu68j4rdt) {
  d: path("M9.75 2.25L12 4.5L9.75 6.75m-1.25 3h7m-7 2.75h7m-7 2.75H13");
}

</style>
