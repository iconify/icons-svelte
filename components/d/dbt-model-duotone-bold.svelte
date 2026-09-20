<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="lblndgb4u"/><path class="tks4a4biu"/><path class="pt-3kkb2k"/><path class="ae0h5kb0o"/><path class="ap-9ro6ho"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dbt-model-duotone-bold" {...props}></Icon>
<style>
:global(.ae0h5kb0o) {
  d: path("M9 15h6");
}

:global(.ap-9ro6ho) {
  d: path("m8 17 2 2 4 -4");
}

:global(.lblndgb4u) {
  fill: currentColor;
  d: path("M13 3H6v18h12V8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.pt-3kkb2k) {
  d: path("M9 11h6");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tks4a4biu) {
  d: path("M13 3H6v18h12V8Z");
}

</style>
