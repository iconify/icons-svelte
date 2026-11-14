<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e6f7l-b6c"/><path class="gss9qvb8e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:play-diagram" {...props}></Icon>
<style>
:global(.e6f7l-b6c) {
  d: path("M3 17a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0M15.5 3.5l5 5m0-5l-5 5m-9 2.25c0-3 2-4.25 6-4.25");
}

:global(.gss9qvb8e) {
  d: path("m10.5 4.5l2 2l-2 2");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
