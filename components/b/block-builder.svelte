<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pqik8ebqd"/><path class="dzl4wvbnv"/><path class="t9n1jmbej"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:block-builder" {...props}></Icon>
<style>
:global(.dzl4wvbnv) {
  d: path("m15.735 8.914l2.5 1.406A1.5 1.5 0 0 1 19 11.627v2.746a1.5 1.5 0 0 1-.765 1.307l-2.5 1.406a1.5 1.5 0 0 1-1.47 0l-2.5-1.406A1.5 1.5 0 0 1 11 14.373v-2.746a1.5 1.5 0 0 1 .765-1.307l2.5-1.406a1.5 1.5 0 0 1 1.47 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pqik8ebqd) {
  d: path("M4 21.5V3h14M4 7.5L8.5 3M15 3v5.5");
}

:global(.t9n1jmbej) {
  d: path("M11 10.75L15 13l4-2.25M15 13v4.5");
}

</style>
