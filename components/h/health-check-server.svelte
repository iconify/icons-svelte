<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cys7ydbni"/><path class="fkcg0w6by"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:health-check-server" {...props}></Icon>
<style>
:global(.cys7ydbni) {
  d: path("M6 3h10a3.5 3.5 0 0 1 3.5 3.5v5A3.5 3.5 0 0 1 16 15H6a3.5 3.5 0 0 1-3.5-3.5v-5A3.5 3.5 0 0 1 6 3");
}

:global(.fkcg0w6by) {
  d: path("M5.5 9H8l1.5-3l2 6L13 9h3m-1.25 9l2 2L21 15.75");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
