<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ir77sxbxc"/><path class="vqqpf8dpx"/><path class="mvdjtxbun"/><path class="kfs1394gk"/><path class="p2jp-6g9f"/><path class="gmguvrbuj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:episodic-memory-duotone-regular" {...props}></Icon>
<style>
:global(.gmguvrbuj) {
  d: path("M16.5 8.5V11H19");
}

:global(.ir77sxbxc) {
  fill: currentColor;
  d: path("M11 11a5.5 5.5 0 1 0 11 0 5.5 5.5 0 1 0 -11 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.kfs1394gk) {
  d: path("M2 16h6");
}

:global(.mvdjtxbun) {
  d: path("M2 11h6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p2jp-6g9f) {
  d: path("M11 11a5.5 5.5 0 1 0 11 0 5.5 5.5 0 1 0 -11 0");
}

:global(.vqqpf8dpx) {
  d: path("M2 6h6");
}

</style>
