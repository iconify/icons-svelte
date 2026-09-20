<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ybjmfcoaj"/><path class="icp673bbo"/><path class="m80f-vb-j"/><path class="zb0anhelb"/><path class="a-97alb2g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:conformed-dimension-outline-thin" {...props}></Icon>
<style>
:global(.a-97alb2g) {
  d: path("M15.5 17a2 2 0 0 1 2 -2H20a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-2.5a2 2 0 0 1 -2 -2Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.icp673bbo) {
  d: path("M12 9v3");
}

:global(.m80f-vb-j) {
  d: path("M5 15v-3h14v3");
}

:global(.ybjmfcoaj) {
  d: path("M7 4a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H9a2 2 0 0 1 -2 -2Z");
}

:global(.zb0anhelb) {
  d: path("M2 17a2 2 0 0 1 2 -2h2.5a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
