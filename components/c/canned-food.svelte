<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jnxli-b4k"/><path class="ri-sflbbi"/><path class="albr56pca"/><path class="bkm_4czst"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:canned-food" {...props}></Icon>
<style>
:global(.albr56pca) {
  d: path("M13.5 9.75v10.5a3.75 1.25 0 0 0 7.5 0V9.75M3 10a3.75 1.25 0 0 0 7.5 0M3 15.5a3.75 1.25 0 0 0 7.5 0");
}

:global(.bkm_4czst) {
  d: path("M13.5 13.5a3.75 1.25 0 0 0 7.5 0m-7.5 3.75a3.75 1.25 0 0 0 7.5 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jnxli-b4k) {
  d: path("M3 5.25a3.75 1.25 0 1 0 7.5 0a3.75 1.25 0 1 0-7.5 0");
}

:global(.ri-sflbbi) {
  d: path("M3 5.25v15a3.75 1.25 0 0 0 7.5 0v-15m3 4.5a3.75 1.25 0 1 0 7.5 0a3.75 1.25 0 1 0-7.5 0");
}

</style>
