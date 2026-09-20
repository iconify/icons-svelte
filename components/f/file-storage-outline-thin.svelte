<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u__n76blo"/><path class="ivc0p9bus"/><path class="gnhsdzb8d"/><path class="t-ezw9csu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:file-storage-outline-thin" {...props}></Icon>
<style>
:global(.gnhsdzb8d) {
  d: path("M6 13h6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ivc0p9bus) {
  d: path("M6 4h12");
}

:global(.t-ezw9csu) {
  d: path("M6 16h9");
}

:global(.u__n76blo) {
  d: path("M2 10a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
