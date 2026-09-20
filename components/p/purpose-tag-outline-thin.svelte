<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bn_pu6j-z"/><path class="q866-it_d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:purpose-tag-outline-thin" {...props}></Icon>
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

:global(.q866-it_d) {
  d: path("M9 10.5h3l3 3 -3 3H9Z");
}

</style>
