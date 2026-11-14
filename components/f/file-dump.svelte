<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ivx36be4o"/><path class="mmitn_bxa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:file-dump" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ivx36be4o) {
  d: path("M9 2.5h5l3 3v5a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2v-6a2 2 0 0 1 2-2m-5.5 14v3a2 2 0 0 0 2 2h13a2 2 0 0 0 2-2v-3m-8.5-4v6");
}

:global(.mmitn_bxa) {
  d: path("m9.5 16l2.5 2.5l2.5-2.5");
}

</style>
