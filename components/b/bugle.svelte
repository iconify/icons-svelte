<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pehfr6elc"/><path class="b9z_t4bak"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bugle" {...props}></Icon>
<style>
:global(.b9z_t4bak) {
  d: path("M5 14a5 4.5 0 1 0 10 0a5 4.5 0 1 0-10 0M3 8v3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pehfr6elc) {
  d: path("M3 9.5h11c3 0 5-1.75 7-3.5v7c-2-1.75-4-3.5-7-3.5");
}

</style>
