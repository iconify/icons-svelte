<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cecss-llv"/><path class="ov8wgi42r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:fishing-swivel" {...props}></Icon>
<style>
:global(.cecss-llv) {
  d: path("M9.25 5.25a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ov8wgi42r) {
  d: path("M12 8za1.75 1.75 0 0 1 1.75 1.75v1A1.75 1.75 0 0 1 12 12.5a1.75 1.75 0 0 1-1.75-1.75v-1A1.75 1.75 0 0 1 12 8m0 4.5l-2.5 3V19a2.5 2.5 0 0 0 5 0v-3.5");
}

</style>
