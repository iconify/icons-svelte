<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kwgk8l3ak"/><path class="p3xmfebiu"/><path class="bl3497szx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:gable-roof" {...props}></Icon>
<style>
:global(.bl3497szx) {
  d: path("m10.875 12.875l.064-.064a1.5 1.5 0 0 1 2.122 0l.064.064A.659.659 0 0 1 12.659 14h-1.318a.659.659 0 0 1-.466-1.125");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kwgk8l3ak) {
  d: path("M2.5 14L12 4l9.5 10");
}

:global(.p3xmfebiu) {
  d: path("M5 21.5V15l7-7.5l7 7.5v6.5");
}

</style>
