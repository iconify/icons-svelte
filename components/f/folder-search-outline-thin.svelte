<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bn_pu6j-z"/><path class="lp21zybfl"/><path class="vpqn33bbz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:folder-search-outline-thin" {...props}></Icon>
<style>
:global(.bn_pu6j-z) {
  d: path("M20 7v13H4V4h5l3 3h4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lp21zybfl) {
  d: path("M8.5 13a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.vpqn33bbz) {
  d: path("m13.5 15 2.5 2.5");
}

</style>
