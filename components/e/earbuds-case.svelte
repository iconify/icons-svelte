<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m17c8xsca"/><path class="xi9eqh2nl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:earbuds-case" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m17c8xsca) {
  d: path("M9 5.5h6a6.5 6.5 0 0 1 6.5 6.5a6.5 6.5 0 0 1-6.5 6.5H9A6.5 6.5 0 0 1 2.5 12A6.5 6.5 0 0 1 9 5.5M2.5 10h19");
}

:global(.xi9eqh2nl) {
  fill: currentColor;
  d: path("M12 14.25h.01");
}

</style>
