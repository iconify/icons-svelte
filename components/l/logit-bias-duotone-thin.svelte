<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tgd6fuaxe"/><path class="yrana5b4o"/><path class="jy2ryjbrr"/><path class="i6yllfq7b"/><path class="tuwrm3b-r"/><path class="xexu65brv"/><path class="a9dl0vblp"/><path class="k6x6uv-ap"/><path class="s9l3g3b4l"/><path class="du_3_4tit"/><path class="u8rhnqeij"/><path class="dt6efbtua"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:logit-bias-duotone-thin" {...props}></Icon>
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

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i6yllfq7b) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 21.5h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jy2ryjbrr) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 6v13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k6x6uv-ap) {
  d: path("M12 11v8");
}

:global(.s9l3g3b4l) {
  d: path("M18 6v13");
}

:global(.tgd6fuaxe) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 6v13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tuwrm3b-r) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 2.5V5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.u8rhnqeij) {
  d: path("M12 2.5V5");
}

:global(.xexu65brv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9.5 6 12 8.5 14.5 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yrana5b4o) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 11v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
