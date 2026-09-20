<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o4tqyhbip"/><path class="jd882cb_k"/><path class="j33qrnb7r"/><path class="nq0_nyzpb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:iron-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j33qrnb7r) {
  d: path("M10 11c0 -6 7 -6 7 0");
}

:global(.jd882cb_k) {
  d: path("m4 16 5 -5h9v5Z");
}

:global(.nq0_nyzpb) {
  d: path("M4 19h14");
}

:global(.o4tqyhbip) {
  fill: currentColor;
  d: path("m4 16 5 -5h9v5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
