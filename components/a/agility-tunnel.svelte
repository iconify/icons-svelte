<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dns7uqbmn"/><path class="b-bvkjb9c"/><path class="n81iwfhmj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:agility-tunnel" {...props}></Icon>
<style>
:global(.b-bvkjb9c) {
  d: path("M5 6.75q7-3 14 0m-14 12q7-3 14 0m0-12a2.5 6 0 0 1 0 12");
}

:global(.dns7uqbmn) {
  d: path("M2.5 12.75a2.5 6 0 1 0 5 0a2.5 6 0 1 0-5 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n81iwfhmj) {
  d: path("M12 5.25a2.5 6 0 0 1 0 12");
}

</style>
