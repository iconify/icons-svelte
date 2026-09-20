<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="lwdt7zb5f"/><path class="pk1ekjvnl"/><path class="xtovmhbxk"/><path class="codat6b9f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:lane-change-outline-bold" {...props}></Icon>
<style>
:global(.codat6b9f) {
  d: path("M11.5 6H15v3.5");
}

:global(.lwdt7zb5f) {
  d: path("M4 2v20");
}

:global(.pk1ekjvnl) {
  d: path("M20 2v20");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.xtovmhbxk) {
  d: path("M9 19v-7l6 -6");
}

</style>
