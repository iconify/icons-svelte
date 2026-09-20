<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p3_ik-83z"/><path class="cu_n5qbwp"/><path class="e19f68q3l"/><path class="f9dbawa5o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:callout-outline-thin" {...props}></Icon>
<style>
:global(.cu_n5qbwp) {
  d: path("m7 9 -3 3 3 3");
}

:global(.e19f68q3l) {
  d: path("M10 9h9");
}

:global(.f9dbawa5o) {
  d: path("M10 13h9");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.p3_ik-83z) {
  d: path("M7 6a2 2 0 0 1 2 -2h11a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H9a2 2 0 0 1 -2 -2Z");
}

</style>
