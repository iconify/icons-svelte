<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sk4_mtx5w"/><path class="nimx5w1ex"/><path class="w5z_myj4u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:fallback-model-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nimx5w1ex) {
  d: path("M12 11.5V16");
}

:global(.sk4_mtx5w) {
  d: path("M12 2.5 16.5 7 12 11.5 7.5 7Z");
}

:global(.w5z_myj4u) {
  d: path("m12 16 2.5 2.5L12 21l-2.5 -2.5Z");
}

</style>
