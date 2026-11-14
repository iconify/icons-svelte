<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o0kadqjah"/><path class="p58_jqboz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:hill-climb-bike" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o0kadqjah) {
  d: path("m2.5 20l19-11m-19 3.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m8.25-4.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

:global(.p58_jqboz) {
  d: path("m5 12.5l2.75-5.75l5.5 1m0 0L12 3.5h2");
}

</style>
