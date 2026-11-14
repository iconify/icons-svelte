<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iwm01y5dj"/><path class="t3tlwge1z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:fern" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iwm01y5dj) {
  d: path("M12 3v18.5m-7-8q.5 3 7 4.5q6.5-1.5 7-4.5");
}

:global(.t3tlwge1z) {
  d: path("M6.5 9q.5 3 5.5 4.5Q17 12 17.5 9m-9-4Q9 7.5 12 9q3-1.5 3.5-4");
}

</style>
