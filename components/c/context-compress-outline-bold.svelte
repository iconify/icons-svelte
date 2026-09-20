<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="b4x_isbqv"/><path class="d_6ujebpi"/><path class="qhy91zm_e"/><path class="a9xckwbov"/><path class="qlfruhq7c"/><path class="br_h3vzli"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:context-compress-outline-bold" {...props}></Icon>
<style>
:global(.a9xckwbov) {
  d: path("m9 10 2 2 -2 2");
}

:global(.b4x_isbqv) {
  d: path("M8 6H5v12h3");
}

:global(.br_h3vzli) {
  d: path("m15 10 -2 2 2 2");
}

:global(.d_6ujebpi) {
  d: path("M16 6h3v12h-3");
}

:global(.qhy91zm_e) {
  d: path("M6 12h5");
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

</style>
