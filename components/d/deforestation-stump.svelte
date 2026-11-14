<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hde3qetzm"/><path class="dzo-c2hxo"/><path class="he77yqknm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:deforestation-stump" {...props}></Icon>
<style>
:global(.dzo-c2hxo) {
  d: path("M5 7.5v10q0 1.5-1.5 3h17Q19 19 19 17.5v-10");
}

:global(.hde3qetzm) {
  d: path("M5 7.5a7 3.5 0 1 0 14 0a7 3.5 0 1 0-14 0Z");
}

:global(.he77yqknm) {
  d: path("M9 7.5a3 1 0 1 0 6 0a3 1 0 1 0-6 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
