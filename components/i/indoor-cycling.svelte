<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uezo0ebqd"/><circle class="ki9xavbtw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:indoor-cycling" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ki9xavbtw) {
  cx: 15.75px;
  cy: 15.5px;
  r: 3px;
}

:global(.uezo0ebqd) {
  d: path("M3.25 21.25h17.5m-15 0L9.25 9m-2.5 0h4.75m-3.25 3.5h8.1m-.6 3l2-10.25h2.5");
}

</style>
