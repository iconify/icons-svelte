<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="tw3a5bcpe"/><path class="lpthwr95f"/><path class="qlfruhq7c"/><path class="zpl29uvhf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:alignment-outline-bold" {...props}></Icon>
<style>
:global(.lpthwr95f) {
  d: path("M3 17h6l4 -4");
}

:global(.qlfruhq7c) {
  d: path("M13 12h5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tw3a5bcpe) {
  d: path("M3 7h6l4 4");
}

:global(.zpl29uvhf) {
  d: path("m16 9 3 3 -3 3");
}

</style>
