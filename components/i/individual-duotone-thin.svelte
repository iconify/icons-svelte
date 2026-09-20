<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pmt-nxb9a"/><path class="n92hyrp1a"/><path class="on0zajbot"/><path class="qik8460ao"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:individual-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n92hyrp1a) {
  d: path("M9 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.on0zajbot) {
  d: path("M7 17a5 5 0 0 1 10 0");
}

:global(.pmt-nxb9a) {
  fill: currentColor;
  d: path("M9 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.qik8460ao) {
  d: path("M5 21h14");
}

</style>
