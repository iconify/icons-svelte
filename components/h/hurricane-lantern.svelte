<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k-747lbuo"/><path class="z_jr7polf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:hurricane-lantern" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k-747lbuo) {
  d: path("M10 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

:global(.z_jr7polf) {
  d: path("M8 9h8l-1.5-2h-5Zm.5 0c-2 2.5-2 6.5 0 9h7c2-2.5 2-6.5 0-9m-7.25 9h7.5a1.75 1.75 0 0 1 1.75 1.75a1.75 1.75 0 0 1-1.75 1.75h-7.5a1.75 1.75 0 0 1-1.75-1.75A1.75 1.75 0 0 1 8.25 18m1.5-9v9m4.5-9v9");
}

</style>
