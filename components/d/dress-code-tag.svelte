<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d13qe3hws"/><path class="bbsgmkycs"/><path class="qzpl9lj5f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:dress-code-tag" {...props}></Icon>
<style>
:global(.bbsgmkycs) {
  d: path("M10.5 9.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

:global(.d13qe3hws) {
  d: path("M12 4.5L18 9v10.5q0 2-2 2H8q-2 0-2-2V9Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qzpl9lj5f) {
  d: path("M12 8q0-5.5 4.5-5.5M9 13.75l3 2l3-2v5l-3-2l-3 2Z");
}

</style>
