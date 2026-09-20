<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lv2tvb6se"/><path class="l8dn9jbyp"/><path class="olqfcgidt"/><path class="fqgwxackw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:calm-duotone-regular" {...props}></Icon>
<style>
:global(.fqgwxackw) {
  d: path("M12 4c5 0 8 3 8 8 -5 0 -8 -3 -8 -8");
}

:global(.l8dn9jbyp) {
  d: path("M2 15h20");
}

:global(.lv2tvb6se) {
  fill: currentColor;
  d: path("M12 4c5 0 8 3 8 8 -5 0 -8 -3 -8 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.olqfcgidt) {
  d: path("M6 19h12");
}

</style>
