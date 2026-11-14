<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ud7qvmbhh"/><path class="nm1m4obuo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:fabric-bolt" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nm1m4obuo) {
  d: path("M6 3h12.5a3 4.5 0 0 1 0 9H6m0 0l-1.5 8.5h13l1-8.5");
}

:global(.ud7qvmbhh) {
  d: path("M3 7.5a3 4.5 0 1 0 6 0a3 4.5 0 1 0-6 0");
}

</style>
