<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j9p9_iblm"/><path class="kgattoamf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:beauty-dish" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j9p9_iblm) {
  d: path("M2.5 6.5a9.5 3 0 1 0 19 0a9.5 3 0 1 0-19 0");
}

:global(.kgattoamf) {
  d: path("M2.5 6.5c1 6 5 8.5 9.5 8.5s8.5-2.5 9.5-8.5M12 15v5.5m-2-14h4");
}

</style>
