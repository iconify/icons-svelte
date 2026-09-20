<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i_bq1yb3z"/><path class="ha190wb6v"/><path class="l0v-b4kbr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:hydration-alert-outline-regular" {...props}></Icon>
<style>
:global(.ha190wb6v) {
  d: path("M10 8V4h4v4");
}

:global(.i_bq1yb3z) {
  d: path("M8 8v12h8V8Z");
}

:global(.l0v-b4kbr) {
  d: path("M8 12h8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
