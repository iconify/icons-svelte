<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jaee2j7fj"/><path class="su1urnbta"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cylinder" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jaee2j7fj) {
  d: path("M4.5 6a7.5 3 0 1 0 15 0a7.5 3 0 1 0-15 0");
}

:global(.su1urnbta) {
  d: path("M4.5 6v12a7.5 3 0 0 0 15 0V6");
}

</style>
