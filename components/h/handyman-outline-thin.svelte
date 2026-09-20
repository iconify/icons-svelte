<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k74vnib1e"/><path class="fqjewfbna"/><path class="bkx9mvb8q"/><path class="c744qo9dt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:handyman-outline-thin" {...props}></Icon>
<style>
:global(.bkx9mvb8q) {
  d: path("M14 20v-7h8v7Z");
}

:global(.c744qo9dt) {
  d: path("M16 13v-3h4v3");
}

:global(.fqjewfbna) {
  d: path("M2 16a4 4 0 0 1 8 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k74vnib1e) {
  d: path("M3 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
