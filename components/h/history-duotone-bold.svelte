<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="cf7uocc2a"/><path class="afo552p2d"/><path class="intvnpcjd"/><path class="r1oykbb0j"/><path class="kv86m5bsi"/><path class="pfpu_3ppl"/><path class="dm5ccobgo"/><path class="mcj52c2nx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:history-duotone-bold" {...props}></Icon>
<style>
:global(.afo552p2d) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 8v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cf7uocc2a) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 4v5h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dm5ccobgo) {
  d: path("M12 12h4");
}

:global(.intvnpcjd) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 12h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kv86m5bsi) {
  d: path("M3 4v5h5");
}

:global(.mcj52c2nx) {
  d: path("M12 3a9 9 0 1 1 -9 9");
}

:global(.pfpu_3ppl) {
  d: path("M12 8v4");
}

:global(.r1oykbb0j) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 3a9 9 0 1 1 -9 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
