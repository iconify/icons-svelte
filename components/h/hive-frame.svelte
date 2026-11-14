<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j_psw1y4g"/><path class="xp1mmvbgl"/><path class="u6tlzewpz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:hive-frame" {...props}></Icon>
<style>
:global(.j_psw1y4g) {
  d: path("M3 3h18v18H3Z");
}

:global(.u6tlzewpz) {
  d: path("m9 11l3 1.75v3.5L9 18l-3-1.75v-3.5Zm6 0l3 1.75v3.5L15 18l-3-1.75v-3.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xp1mmvbgl) {
  d: path("m12 5.75l3 1.75V11l-3 1.75L9 11V7.5Z");
}

</style>
