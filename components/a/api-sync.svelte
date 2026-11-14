<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n3opjgvay"/><path class="qbgp8rbjl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:api-sync" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n3opjgvay) {
  d: path("M4.5 12a7.6 7.6 0 0 1 13.25-5m1.75 5a7.6 7.6 0 0 1-13.25 5");
}

:global(.qbgp8rbjl) {
  d: path("M17.75 4v3h-3m-8.5 13v-3h3");
}

</style>
