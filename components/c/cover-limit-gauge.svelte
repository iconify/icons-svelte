<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ev8l0ej4e"/><path class="mdmu77b1v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cover-limit-gauge" {...props}></Icon>
<style>
:global(.ev8l0ej4e) {
  d: path("M3.773 19.25a9.5 9.5 0 1 1 16.454 0M12 14.5l4-4.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mdmu77b1v) {
  d: path("M10.5 14.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M12 6v1.5M5.25 10l1.25 1m12.25-1l-1.25 1");
}

</style>
