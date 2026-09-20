<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="a9dl0vblp"/><path class="k6x6uv-ap"/><path class="s9l3g3b4l"/><path class="du_3_4tit"/><path class="u8rhnqeij"/><path class="dt6efbtua"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:logit-bias-outline-bold" {...props}></Icon>
<style>
:global(.a9dl0vblp) {
  d: path("M6 6v13");
}

:global(.dt6efbtua) {
  d: path("M9.5 6 12 8.5 14.5 6");
}

:global(.du_3_4tit) {
  d: path("M4 21.5h16");
}

:global(.k6x6uv-ap) {
  d: path("M12 11v8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.s9l3g3b4l) {
  d: path("M18 6v13");
}

:global(.u8rhnqeij) {
  d: path("M12 2.5V5");
}

</style>
