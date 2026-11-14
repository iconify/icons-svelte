<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uq7p7i26k"/><path class="l29x5xuij"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ab-flag" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l29x5xuij) {
  d: path("M4.75 16.5L7 7.5l2.25 9m-3.5-3h2.5m6.5 3v-9h2a2 2 0 0 1 0 4h-2m2 0a2.5 2.5 0 0 1 0 5h-2");
}

:global(.uq7p7i26k) {
  d: path("M6.375 4h11.25A4.375 4.375 0 0 1 22 8.375v7.25A4.375 4.375 0 0 1 17.625 20H6.375A4.375 4.375 0 0 1 2 15.625v-7.25A4.375 4.375 0 0 1 6.375 4M12 4v16");
}

</style>
