<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o903avb-o"/><path class="jlj43xbts"/><path class="xrifsibej"/><path class="tldtqlb3m"/><path class="a1iadc4sf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:newspaper-outline-thin" {...props}></Icon>
<style>
:global(.a1iadc4sf) {
  d: path("M4 13h12");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jlj43xbts) {
  d: path("M18 9h4v8h-4");
}

:global(.o903avb-o) {
  d: path("M2 19V6h16v13Z");
}

:global(.tldtqlb3m) {
  d: path("M10 13v4");
}

:global(.xrifsibej) {
  d: path("M4 10h12");
}

</style>
