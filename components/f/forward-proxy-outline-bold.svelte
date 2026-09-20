<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="z3v4a-b3b"/><path class="he2cqebcu"/><path class="tdc4xtbqn"/><path class="vzsad0b2k"/><path class="qaaffjxln"/><path class="vijdpmg8r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:forward-proxy-outline-bold" {...props}></Icon>
<style>
:global(.he2cqebcu) {
  d: path("M2 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.qaaffjxln) {
  d: path("M10 12h5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tdc4xtbqn) {
  d: path("M2 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.vijdpmg8r) {
  d: path("M15 10a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
}

:global(.vzsad0b2k) {
  d: path("m4 6 6 6 -6 6");
}

:global(.z3v4a-b3b) {
  d: path("M2 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
