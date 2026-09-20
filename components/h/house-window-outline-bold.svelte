<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="p52nwacub"/><path class="vc1mckb3d"/><path class="a5tuk3h7e"/><path class="cjsg0ab2y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:house-window-outline-bold" {...props}></Icon>
<style>
:global(.a5tuk3h7e) {
  d: path("M4 10h16");
}

:global(.cjsg0ab2y) {
  d: path("M2 20h20");
}

:global(.p52nwacub) {
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vc1mckb3d) {
  d: path("M12 3v14");
}

</style>
