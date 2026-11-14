<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vq20h_bls"/><path class="nt2vl3bos"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:input-field-focused" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nt2vl3bos) {
  d: path("M7.375 7.75h9.25a2.625 2.625 0 0 1 2.625 2.625v3.25a2.625 2.625 0 0 1-2.625 2.625h-9.25a2.625 2.625 0 0 1-2.625-2.625v-3.25A2.625 2.625 0 0 1 7.375 7.75m.375 2.75v3");
}

:global(.vq20h_bls) {
  d: path("M9 5h6a7 7 0 0 1 7 7a7 7 0 0 1-7 7H9a7 7 0 0 1-7-7a7 7 0 0 1 7-7");
}

</style>
