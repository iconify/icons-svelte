<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hpo_a-hcx"/><path class="kvjodjb4w"/><path class="wp3t31v6b"/><path class="p9t_2jr2d"/><path class="wpqcgi2_k"/><path class="xotxp7bir"/><path class="vlspyzbym"/><path class="tl5daebtp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:biodiversity-duotone-bold" {...props}></Icon>
<style>
:global(.hpo_a-hcx) {
  fill: currentColor;
  d: path("M10 5c0 6 -3 9 -8 9 0 -6 3 -9 8 -9");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.kvjodjb4w) {
  fill: currentColor;
  d: path("M12 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.p9t_2jr2d) {
  fill: currentColor;
  d: path("M13 16a5 5 0 0 1 9 0 4 4 0 0 1 -4.5 4 4 4 0 0 1 -4.5 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tl5daebtp) {
  d: path("M13 16a5 5 0 0 1 9 0 4 4 0 0 1 -4.5 4 4 4 0 0 1 -4.5 -4");
}

:global(.vlspyzbym) {
  d: path("M17 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.wp3t31v6b) {
  fill: currentColor;
  d: path("M17 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.wpqcgi2_k) {
  d: path("M10 5c0 6 -3 9 -8 9 0 -6 3 -9 8 -9");
}

:global(.xotxp7bir) {
  d: path("M12 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
