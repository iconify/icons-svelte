<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j_psw1y4g"/><path class="nct7lub7f"/><path class="hvrmw7b7m"/><path class="ah3yi8onm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:blend-screen" {...props}></Icon>
<style>
:global(.ah3yi8onm) {
  d: path("M11.25 13.75a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

:global(.hvrmw7b7m) {
  d: path("M6.75 13.75a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

:global(.j_psw1y4g) {
  d: path("M3 3h18v18H3Z");
}

:global(.nct7lub7f) {
  d: path("M9 9.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
