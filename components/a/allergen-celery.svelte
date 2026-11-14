<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="gsezk9b5a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:allergen-celery" {...props}></Icon>
<style>
:global(.gsezk9b5a) {
  d: path("M12 11za1.5 1.5 0 0 1 1.5 1.5v4A1.5 1.5 0 0 1 12 18a1.5 1.5 0 0 1-1.5-1.5v-4A1.5 1.5 0 0 1 12 11m0 0c0-2-1.25-3.25-3-3.5m3 3.5c0-2 1.25-3.25 3-3.5M12 11V6.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oy9aotbsd) {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0");
}

</style>
