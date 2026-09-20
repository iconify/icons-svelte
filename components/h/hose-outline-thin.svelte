<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s3aj37b5a"/><path class="rgnpgnbjr"/><path class="nvz2drb7k"/><path class="lbejogjbx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:hose-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lbejogjbx) {
  d: path("M8 10c-3 0 -4 3 -4 7");
}

:global(.nvz2drb7k) {
  d: path("M10 12v5h3");
}

:global(.rgnpgnbjr) {
  d: path("M16 10h5");
}

:global(.s3aj37b5a) {
  d: path("M8 8h8v4H8Z");
}

</style>
