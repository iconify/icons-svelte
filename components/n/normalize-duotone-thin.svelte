<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="earhjk-cy"/><path class="qcol0s9_v"/><path class="syr202grk"/><path class="kqmw49zer"/><path class="hf_gtezns"/><path class="xgrfb-bqu"/><path class="o759xmblc"/><path class="h7bcztycq"/><path class="c27cgq4un"/><path class="xyj-l9cjp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:normalize-duotone-thin" {...props}></Icon>
<style>
:global(.c27cgq4un) {
  d: path("M18 8v8");
}

:global(.earhjk-cy) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h7bcztycq) {
  d: path("M12 8v8");
}

:global(.hf_gtezns) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kqmw49zer) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.o759xmblc) {
  d: path("M6 8v8");
}

:global(.qcol0s9_v) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.syr202grk) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xgrfb-bqu) {
  d: path("M3 6h18");
}

:global(.xyj-l9cjp) {
  d: path("M3 18h18");
}

</style>
