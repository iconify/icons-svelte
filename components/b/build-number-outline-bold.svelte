<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="b0hkzgbgd"/><path class="wuk2mlziz"/><path class="wj4ljftik"/><path class="qhoa1bbcv"/><path class="l0zc9ibud"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:build-number-outline-bold" {...props}></Icon>
<style>
:global(.b0hkzgbgd) {
  d: path("M4 6a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

:global(.l0zc9ibud) {
  d: path("M8 10h8");
}

:global(.qhoa1bbcv) {
  d: path("M14 7v6");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wj4ljftik) {
  d: path("M10 7v6");
}

:global(.wuk2mlziz) {
  d: path("M7 19h10");
}

</style>
