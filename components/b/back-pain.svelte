<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="l6ygoqbfm"/><path class="a1sjpmb7n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:back-pain" {...props}></Icon>
<style>
:global(.a1sjpmb7n) {
  d: path("M9.25 8.25c2.75.5 4.75 2.5 5.25 5.25L12 21.25m2.5-7.75l2.5 7.75m-7.5-12L7.75 14M19.5 5.25L17.25 8.5h3L18 11.75");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l6ygoqbfm) {
  cx: 7.75px;
  cy: 4.75px;
  r: 2px;
}

</style>
