<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dm_ar8wjk"/><path class="z5u11lbdo"/><path class="z4f7qacqo"/><path class="g9c4ykb9u"/><path class="myi37dz6l"/><path class="syk7o8b5x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:list-checks-outline-thin" {...props}></Icon>
<style>
:global(.dm_ar8wjk) {
  d: path("m3 7 2 2 3 -3");
}

:global(.g9c4ykb9u) {
  d: path("M11 12h10");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.myi37dz6l) {
  d: path("m3 17 2 2 3 -3");
}

:global(.syk7o8b5x) {
  d: path("M11 17h10");
}

:global(.z4f7qacqo) {
  d: path("m3 12 2 2 3 -3");
}

:global(.z5u11lbdo) {
  d: path("M11 7h10");
}

</style>
