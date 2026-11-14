<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rcijpqbmn"/><path class="o9s9q-8-c"/><path class="oloj4_b8s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:firewood" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o9s9q-8-c) {
  d: path("M7.5 8.25a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0M5.75 16a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m9 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

:global(.oloj4_b8s) {
  d: path("M10.25 8.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

:global(.rcijpqbmn) {
  d: path("M3 16a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0m9 0a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0");
}

</style>
