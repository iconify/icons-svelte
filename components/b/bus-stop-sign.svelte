<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s3qjrft8y"/><path class="hqo33gbny"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bus-stop-sign" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hqo33gbny) {
  d: path("M11.125 5.5h1.75A2.625 2.625 0 0 1 15.5 8.125v1.25A2.625 2.625 0 0 1 12.875 12h-1.75A2.625 2.625 0 0 1 8.5 9.375v-1.25A2.625 2.625 0 0 1 11.125 5.5M8.5 8.75h7");
}

:global(.s3qjrft8y) {
  d: path("M9.375 2.5h5.25A4.375 4.375 0 0 1 19 6.875v3.75A4.375 4.375 0 0 1 14.625 15h-5.25A4.375 4.375 0 0 1 5 10.625v-3.75A4.375 4.375 0 0 1 9.375 2.5M12 15v6.5m-3 0h6");
}

</style>
