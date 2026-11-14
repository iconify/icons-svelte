<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n0_72tbrl"/><path class="spy07ybot"/><path class="e2nnbnb5l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:layers" {...props}></Icon>
<style>
:global(.e2nnbnb5l) {
  d: path("m3 16l9 5l9-5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n0_72tbrl) {
  d: path("m12.85 3.472l5.396 2.998a1.75 1.75 0 0 1 0 3.06l-5.396 2.998a1.75 1.75 0 0 1-1.7 0L5.754 9.53a1.75 1.75 0 0 1 0-3.06l5.396-2.998a1.75 1.75 0 0 1 1.7 0");
}

:global(.spy07ybot) {
  d: path("m3 12l9 5l9-5");
}

</style>
