<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k74vnib1e"/><path class="mw9rhebcm"/><path class="tlxtedbcg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:body-fat-outline-thin" {...props}></Icon>
<style>
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

:global(.mw9rhebcm) {
  d: path("M2 16a4.5 4.5 0 0 1 9 0");
}

:global(.tlxtedbcg) {
  d: path("m17 8 5 5a5 5 0 1 1 -10 0Z");
}

</style>
