<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n0n63pb2v"/><path class="nrad3_umv"/><path class="gib7r1bvf"/><path class="u41hfsjfh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:key-escrow-outline-thin" {...props}></Icon>
<style>
:global(.gib7r1bvf) {
  d: path("M12 9.5V12");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n0n63pb2v) {
  d: path("M4 15v4h16v-4");
}

:global(.nrad3_umv) {
  d: path("M10 7.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.u41hfsjfh) {
  d: path("M12 10.5h2.5");
}

</style>
