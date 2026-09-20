<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nreq_9ofo"/><path class="csyuhrrop"/><path class="auud-gbvk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:invoice-overdue-outline-thin" {...props}></Icon>
<style>
:global(.auud-gbvk) {
  d: path("M9.5 6.5h5l-5 5h5Z");
}

:global(.csyuhrrop) {
  d: path("M5 14V3h14v11");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nreq_9ofo) {
  d: path("M2 11v10h20V11L12 21Z");
}

</style>
