<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="tahjarbfs"/><path class="rw6ho_bav"/><path class="ftjlxk3sh"/><path class="dgur4c9cy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:motel-outline-bold" {...props}></Icon>
<style>
:global(.dgur4c9cy) {
  d: path("M14 21v-3.5h4V21");
}

:global(.ftjlxk3sh) {
  d: path("M4 21v-3.5h4V21");
}

:global(.rw6ho_bav) {
  d: path("M2 9h20");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tahjarbfs) {
  d: path("M2 15V5h20v10");
}

</style>
