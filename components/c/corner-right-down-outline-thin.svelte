<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g5tlcslpz"/><path class="c1nxh3m2e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:corner-right-down-outline-thin" {...props}></Icon>
<style>
:global(.c1nxh3m2e) {
  d: path("m9 15 5 5 5 -5");
}

:global(.g5tlcslpz) {
  d: path("M4 4h10v16");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
