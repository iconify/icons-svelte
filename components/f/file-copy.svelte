<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="anvv0bcxo"/><path class="qjswwebqn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:file-copy" {...props}></Icon>
<style>
:global(.anvv0bcxo) {
  d: path("M9 6h5.5l4.5 4.5V19a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qjswwebqn) {
  d: path("M14.5 6v3a1.5 1.5 0 0 0 1.5 1.5h3M4.5 17V5a2 2 0 0 1 2-2H12");
}

</style>
