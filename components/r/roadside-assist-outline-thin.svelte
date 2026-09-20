<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sqwju3bsh"/><path class="du3agkbjb"/><path class="fquh7rbnp"/><path class="a3s-ix6ox"/><path class="mo1bh2_2m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:roadside-assist-outline-thin" {...props}></Icon>
<style>
:global(.a3s-ix6ox) {
  d: path("M12 9.5v6");
}

:global(.du3agkbjb) {
  d: path("M5 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.fquh7rbnp) {
  d: path("M15 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mo1bh2_2m) {
  d: path("M9 12.5h6");
}

:global(.sqwju3bsh) {
  d: path("M2 16V8.5h4L9.5 5h5L18 8.5h4V16Z");
}

</style>
