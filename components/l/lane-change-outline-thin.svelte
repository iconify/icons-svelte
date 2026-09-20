<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lwdt7zb5f"/><path class="pk1ekjvnl"/><path class="xtovmhbxk"/><path class="codat6b9f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:lane-change-outline-thin" {...props}></Icon>
<style>
:global(.codat6b9f) {
  d: path("M11.5 6H15v3.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lwdt7zb5f) {
  d: path("M4 2v20");
}

:global(.pk1ekjvnl) {
  d: path("M20 2v20");
}

:global(.xtovmhbxk) {
  d: path("M9 19v-7l6 -6");
}

</style>
