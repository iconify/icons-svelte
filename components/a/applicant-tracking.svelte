<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u7inuk_nf"/><path class="aejbfsb7s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:applicant-tracking" {...props}></Icon>
<style>
:global(.aejbfsb7s) {
  d: path("M10.5 7a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M2.75 18.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m8 0a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m8 0a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0M8 18.5h.01m7.99 0h.01");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.u7inuk_nf) {
  d: path("M12 13.5S7.5 9.5 7.5 7a4.5 4.5 0 0 1 9 0c0 2.5-4.5 6.5-4.5 6.5");
}

</style>
