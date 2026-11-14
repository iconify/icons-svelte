<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ui09lnbbe"/><path class="yguwicc3t"/><path class="msad3isat"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:post-office" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.msad3isat) {
  d: path("m8 12l4 3l4-3");
}

:global(.ui09lnbbe) {
  d: path("m3 9l9-5l9 5v11.5H3Z");
}

:global(.yguwicc3t) {
  d: path("M9.5 12h5a1.5 1.5 0 0 1 1.5 1.5v2a1.5 1.5 0 0 1-1.5 1.5h-5A1.5 1.5 0 0 1 8 15.5v-2A1.5 1.5 0 0 1 9.5 12");
}

</style>
