<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jta5xzb9q"/><path class="uof4cz1pa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chinchilla" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jta5xzb9q) {
  d: path("M3.5 14a7 7 0 1 0 14 0a7 7 0 1 0-14 0");
}

:global(.uof4cz1pa) {
  d: path("M4.25 6a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M12 5.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M16.25 18C20.5 19.5 22 15 20 12.5m-7.5 0h.01");
}

</style>
