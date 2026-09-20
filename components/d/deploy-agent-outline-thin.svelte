<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fce-vbb2c"/><path class="z6s_w0bbl"/><path class="a7h45wbtv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:deploy-agent-outline-thin" {...props}></Icon>
<style>
:global(.a7h45wbtv) {
  d: path("M15.5 8.5 18 6l2.5 2.5");
}

:global(.fce-vbb2c) {
  d: path("M10.11 9.47a5 5 0 1 1 -4.22 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z6s_w0bbl) {
  d: path("M18 8v11");
}

</style>
