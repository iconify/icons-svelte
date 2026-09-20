<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lblndgb4u"/><path class="tks4a4biu"/><path class="i-xxtdbfm"/><path class="r-3ib9fxz"/><path class="hcn7bdzwu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:file-format-duotone-regular" {...props}></Icon>
<style>
:global(.hcn7bdzwu) {
  d: path("M15 11v7");
}

:global(.i-xxtdbfm) {
  d: path("M9 11v7");
}

:global(.lblndgb4u) {
  fill: currentColor;
  d: path("M13 3H6v18h12V8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.r-3ib9fxz) {
  d: path("M12 11v7");
}

:global(.tks4a4biu) {
  d: path("M13 3H6v18h12V8Z");
}

</style>
