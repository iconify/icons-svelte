<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="okud9xj_d"/><path class="brjpv3b7t"/><path class="raivi4yli"/><path class="uwjz-dbef"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:flight-landed-outline-thin" {...props}></Icon>
<style>
:global(.brjpv3b7t) {
  d: path("M17.5 6.5V11");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.okud9xj_d) {
  d: path("M2 7a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.raivi4yli) {
  d: path("M17.5 13v4.5");
}

:global(.uwjz-dbef) {
  d: path("m9 12 2 2 4 -4");
}

</style>
