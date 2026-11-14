<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hsc39fblp"><path class="zvr6o5b2p"/><path class="vxo3gieyf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:element-astatine" {...props}></Icon>
<style>
:global(.hsc39fblp) {
  fill: currentColor;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vxo3gieyf) {
  d: path("M9 12a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

:global(.zvr6o5b2p) {
  d: path("M5.5 3h13A2.5 2.5 0 0 1 21 5.5v13a2.5 2.5 0 0 1-2.5 2.5h-13A2.5 2.5 0 0 1 3 18.5v-13A2.5 2.5 0 0 1 5.5 3m13 9a6.5 6.5 0 0 0-13 0a6.5 6.5 0 0 0 13 0");
}

</style>
