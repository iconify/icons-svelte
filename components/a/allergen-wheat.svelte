<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rv-rerbli"/><path class="y-mrzhbos"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:allergen-wheat" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rv-rerbli) {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0m9.5 6V6.5");
}

:global(.y-mrzhbos) {
  d: path("M12 15.5c-2 0-3.25-1.25-3.25-3c2 0 3.25 1.25 3.25 3m0 0c2 0 3.25-1.25 3.25-3c-2 0-3.25 1.25-3.25 3m0-4c-2 0-3.25-1.25-3.25-3c2 0 3.25 1.25 3.25 3m0 0c2 0 3.25-1.25 3.25-3c-2 0-3.25 1.25-3.25 3");
}

</style>
