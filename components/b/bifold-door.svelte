<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oq2nkbb8e"/><path class="arnjgwc1g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bifold-door" {...props}></Icon>
<style>
:global(.arnjgwc1g) {
  d: path("m6.5 7l2.75 1.5L12 7l2.75 1.5L17.5 7v10.5L14.75 19L12 17.5L9.25 19L6.5 17.5Zm2.75 1.5V19M12 7v10.5m2.75-9V19");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oq2nkbb8e) {
  d: path("M3 20.5v-17h18v17");
}

</style>
