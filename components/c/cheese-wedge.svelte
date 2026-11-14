<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ayycwrbdl"/><path class="cgtadxb2p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cheese-wedge" {...props}></Icon>
<style>
:global(.ayycwrbdl) {
  d: path("M3.5 17h17v-6l-17-4Z");
}

:global(.cgtadxb2p) {
  d: path("M6.5 13a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m7.25.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
