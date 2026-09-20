<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l8dn9jbyp"/><path class="olqfcgidt"/><path class="fqgwxackw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:calm-outline-thin" {...props}></Icon>
<style>
:global(.fqgwxackw) {
  d: path("M12 4c5 0 8 3 8 8 -5 0 -8 -3 -8 -8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l8dn9jbyp) {
  d: path("M2 15h20");
}

:global(.olqfcgidt) {
  d: path("M6 19h12");
}

</style>
