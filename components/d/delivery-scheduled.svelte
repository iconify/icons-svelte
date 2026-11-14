<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h6huabbyy"/><path class="x8ynn1xmi"/><path class="ba0e33bht"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:delivery-scheduled" {...props}></Icon>
<style>
:global(.ba0e33bht) {
  d: path("m7 10.25l5 2.5l5-2.5m-5 2.5v5.5");
}

:global(.h6huabbyy) {
  d: path("M7 4.5h10A3.5 3.5 0 0 1 20.5 8v9.5A3.5 3.5 0 0 1 17 21H7a3.5 3.5 0 0 1-3.5-3.5V8A3.5 3.5 0 0 1 7 4.5m1-2v4m8-4v4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x8ynn1xmi) {
  d: path("m7 10.25l5-2.5l5 2.5v5.5l-5 2.5l-5-2.5Z");
}

</style>
