<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="md3qg6xkk"/><path class="bvirm9d4j"/><path class="sxlwlmkmh"/><path class="n90p24bmq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:api-bridge-outline-bold" {...props}></Icon>
<style>
:global(.bvirm9d4j) {
  d: path("M20 6v12");
}

:global(.md3qg6xkk) {
  d: path("M4 6v12");
}

:global(.n90p24bmq) {
  d: path("m10 10 2 2 -2 2");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sxlwlmkmh) {
  d: path("M4 12h16");
}

</style>
