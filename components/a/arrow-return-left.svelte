<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hioffvymr"/><path class="c3fkm4ldx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:arrow-return-left" {...props}></Icon>
<style>
:global(.c3fkm4ldx) {
  d: path("m8.5 10.5l-4 4l4 4");
}

:global(.hioffvymr) {
  d: path("M9 5.5h5.5a4.5 4.5 0 0 1 0 9h-10");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
