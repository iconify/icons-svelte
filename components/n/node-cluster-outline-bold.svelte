<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fozhwebbv"/><path class="aq5i5tblx"/><path class="p83l94bht"/><path class="uzmclv6tb"/><path class="fhumgwb1z"/><path class="ko65glbqt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:node-cluster-outline-bold" {...props}></Icon>
<style>
:global(.aq5i5tblx) {
  d: path("M4 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.fhumgwb1z) {
  d: path("m10.5 9.5 -3 3");
}

:global(.fozhwebbv) {
  d: path("M10 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.ko65glbqt) {
  d: path("m13.5 9.5 3 3");
}

:global(.p83l94bht) {
  d: path("M16 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.uzmclv6tb) {
  d: path("M12 8v3");
}

</style>
