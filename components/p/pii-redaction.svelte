<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xtyrqcutl"/><path class="txyevob2f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pii-redaction" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.txyevob2f) {
  d: path("M3.5 16.5H15");
}

:global(.xtyrqcutl) {
  fill: currentColor;
  d: path("M4.75 6.5h14.5A1.75 1.75 0 0 1 21 8.25v1A1.75 1.75 0 0 1 19.25 11H4.75A1.75 1.75 0 0 1 3 9.25v-1A1.75 1.75 0 0 1 4.75 6.5");
}

</style>
