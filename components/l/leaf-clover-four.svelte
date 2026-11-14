<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zkjclebdp"/><path class="htpkuubab"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:leaf-clover-four" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.htpkuubab) {
  d: path("M12 17.5c0 2 .75 3 2.25 4");
}

:global(.zkjclebdp) {
  d: path("M9 7a3.25 3.25 0 1 1 6 0a3.25 3.25 0 1 1 0 6a3.25 3.25 0 1 1-6 0a3.25 3.25 0 1 1 0-6");
}

</style>
