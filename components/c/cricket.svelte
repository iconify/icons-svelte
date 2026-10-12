<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x8j8gccvj"/><circle class="ts3nldyxi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:cricket" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ts3nldyxi) {
  cx: 17.75px;
  cy: 16.75px;
  r: 2.5px;
}

:global(.x8j8gccvj) {
  d: path("m13.14 9.8l1.06 1.06q1.24 1.24 0 2.48L7.84 19.7q-1.24 1.24-2.48 0L4.3 18.64q-1.24-1.24 0-2.48l6.36-6.36q1.24-1.24 2.48 0m.61.45l5-5");
}

</style>
