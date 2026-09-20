<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="bifuny-1t"/><path class="n1soxcq3c"/><path class="vzyxlnb8e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pizza-outline-bold" {...props}></Icon>
<style>
:global(.bifuny-1t) {
  d: path("M12 18 2 8h20Z");
}

:global(.n1soxcq3c) {
  d: path("M8 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vzyxlnb8e) {
  d: path("M14 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
