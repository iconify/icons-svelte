<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hqu8-q-5e"/><path class="ug6ab3blx"/><path class="hrx9ocrcd"/><path class="bos0j4biy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:align-vertical-space-between-outline-bold" {...props}></Icon>
<style>
:global(.bos0j4biy) {
  d: path("M3 21h18");
}

:global(.hqu8-q-5e) {
  d: path("M3 3h18");
}

:global(.hrx9ocrcd) {
  d: path("M7 14h10v4H7Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ug6ab3blx) {
  d: path("M7 6h10v4H7Z");
}

</style>
