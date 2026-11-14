<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s1l-0_bbk"/><path class="xgt97b4ir"/><path class="btp282b5z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:member-bronze" {...props}></Icon>
<style>
:global(.btp282b5z) {
  d: path("M9.25 16.5L12 13.75l2.75 2.75");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.s1l-0_bbk) {
  d: path("M8.25 2.5h.88a1.5 1.5 0 0 1 1.302.756L11 4.25a1.152 1.152 0 0 0 2 0l.568-.994A1.5 1.5 0 0 1 14.87 2.5h.88a1.12 1.12 0 0 1 1.017 1.589l-1.865 4.04A1.5 1.5 0 0 1 13.54 9h-3.08a1.5 1.5 0 0 1-1.362-.871l-1.865-4.04A1.12 1.12 0 0 1 8.25 2.5");
}

:global(.xgt97b4ir) {
  d: path("M5.75 15a6.25 6.25 0 1 0 12.5 0a6.25 6.25 0 1 0-12.5 0");
}

</style>
