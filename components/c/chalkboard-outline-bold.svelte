<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="gkj6vbuly"/><path class="ui32hib9b"/><path class="kwxihke4k"/><path class="wf6qyfbld"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chalkboard-outline-bold" {...props}></Icon>
<style>
:global(.gkj6vbuly) {
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.kwxihke4k) {
  d: path("M7 9h8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ui32hib9b) {
  d: path("M5 20h14");
}

:global(.wf6qyfbld) {
  d: path("M7 13h5");
}

</style>
