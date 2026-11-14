<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d9ggfsbaf"/><path class="bn626dn5u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:design-system-book" {...props}></Icon>
<style>
:global(.bn626dn5u) {
  d: path("m12.53 7.595l.292.738a1.5 1.5 0 0 0 .845.845l.738.292a.57.57 0 0 1 0 1.06l-.738.292a1.5 1.5 0 0 0-.845.845l-.292.738a.57.57 0 0 1-1.06 0l-.292-.738a1.5 1.5 0 0 0-.845-.845l-.738-.292a.57.57 0 0 1 0-1.06l.738-.292a1.5 1.5 0 0 0 .845-.845l.292-.738a.57.57 0 0 1 1.06 0");
}

:global(.d9ggfsbaf) {
  d: path("M5 19.5v-15a2 2 0 0 1 2-2h12v19H7a2 2 0 0 1-2-2a2 2 0 0 1 2-2h12");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
