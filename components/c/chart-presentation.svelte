<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kaxyxosbi"/><path class="t-9y7ebua"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chart-presentation" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kaxyxosbi) {
  d: path("M7.125 4h9.75A2.625 2.625 0 0 1 19.5 6.625v4.25a2.625 2.625 0 0 1-2.625 2.625h-9.75A2.625 2.625 0 0 1 4.5 10.875v-4.25A2.625 2.625 0 0 1 7.125 4M12 2v2m-3.5 9.5l-2 8m9-8l2 8m-5.5-8v8");
}

:global(.t-9y7ebua) {
  d: path("m8 11l2.5-3L13 9.5l3-3");
}

</style>
