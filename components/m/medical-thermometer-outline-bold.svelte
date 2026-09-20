<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nm0sjob8b"/><path class="mwtwrccyv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:medical-thermometer-outline-bold" {...props}></Icon>
<style>
:global(.mwtwrccyv) {
  d: path("m10 15 5 -5");
}

:global(.nm0sjob8b) {
  d: path("M7 19a2.5 2.5 0 0 1 0 -5l9 -9a2.5 2.5 0 0 1 3 3Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
