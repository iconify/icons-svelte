<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tfvr3pske"/><path class="yays23e0d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cabinet-handle-bar" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.tfvr3pske) {
  d: path("M7.125 2.5h9.75A2.625 2.625 0 0 1 19.5 5.125v13.75a2.625 2.625 0 0 1-2.625 2.625h-9.75A2.625 2.625 0 0 1 4.5 18.875V5.125A2.625 2.625 0 0 1 7.125 2.5");
}

:global(.yays23e0d) {
  d: path("M10.5 13.25v-2.5h6v2.5m-9-8v3m0 7.5v3");
}

</style>
