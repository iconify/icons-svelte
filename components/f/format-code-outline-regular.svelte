<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k6nj2fbya"/><path class="rhp6fjekz"/><path class="a-768stfr"/><path class="jkuojibnm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:format-code-outline-regular" {...props}></Icon>
<style>
:global(.a-768stfr) {
  d: path("M8 15h13");
}

:global(.jkuojibnm) {
  d: path("M3 20h18");
}

:global(.k6nj2fbya) {
  d: path("M3 5h18");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rhp6fjekz) {
  d: path("M8 10h13");
}

</style>
