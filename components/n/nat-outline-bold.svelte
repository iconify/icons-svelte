<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="otb2wbb6e"/><path class="wj4cfmbhq"/><path class="ms85c68gf"/><path class="i6ydbdc_n"/><path class="eud-3ptuk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:nat-outline-bold" {...props}></Icon>
<style>
:global(.eud-3ptuk) {
  d: path("M15 12h7");
}

:global(.i6ydbdc_n) {
  d: path("m9 4 6 6v4l-6 6");
}

:global(.ms85c68gf) {
  d: path("M2 20h7");
}

:global(.otb2wbb6e) {
  d: path("M2 4h7");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wj4cfmbhq) {
  d: path("M2 12h7");
}

</style>
