<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mlhqxpbrs"/><path class="eg9sy5n4o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:den" {...props}></Icon>
<style>
:global(.eg9sy5n4o) {
  d: path("M8.5 18.5v-3a3.5 3.5 0 0 1 7 0v3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mlhqxpbrs) {
  d: path("M2.5 18.5C4 8.5 9 5.5 12 5.5s8 3 9.5 13Z");
}

</style>
