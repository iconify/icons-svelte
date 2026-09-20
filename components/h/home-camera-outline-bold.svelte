<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="wwrb2gbkc"/><path class="cj8gecc7a"/><path class="mmsmdzb7p"/><path class="dky0phbxv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:home-camera-outline-bold" {...props}></Icon>
<style>
:global(.cj8gecc7a) {
  d: path("M7 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.dky0phbxv) {
  d: path("M19 11v7");
}

:global(.mmsmdzb7p) {
  d: path("M14 11h5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wwrb2gbkc) {
  d: path("M4 8v6h10V8Z");
}

</style>
