<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="sk4_mtx5w"/><path class="nimx5w1ex"/><path class="w5z_myj4u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:fallback-model-outline-bold" {...props}></Icon>
<style>
:global(.nimx5w1ex) {
  d: path("M12 11.5V16");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sk4_mtx5w) {
  d: path("M12 2.5 16.5 7 12 11.5 7.5 7Z");
}

:global(.w5z_myj4u) {
  d: path("m12 16 2.5 2.5L12 21l-2.5 -2.5Z");
}

</style>
