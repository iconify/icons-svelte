<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ugdbidcqi"/><path class="elc06ob4j"/><path class="hclo6jb2r"/><path class="mxzk029nb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-sandbox-limit-outline-thin" {...props}></Icon>
<style>
:global(.elc06ob4j) {
  d: path("M8 8h8");
}

:global(.hclo6jb2r) {
  d: path("M8 16h8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mxzk029nb) {
  d: path("M12 10v4");
}

:global(.ugdbidcqi) {
  d: path("M16.23 2.94a10 10 0 1 1 -8.46 0");
}

</style>
