<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xi_ig861f"/><path class="kp9hkxojh"/><path class="t4mssrbdw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cymbal-stand" {...props}></Icon>
<style>
:global(.kp9hkxojh) {
  d: path("M9 21.5V10l4-2.75");
}

:global(.t4mssrbdw) {
  d: path("m3.5 21.5l5.5-5l5.5 5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xi_ig861f) {
  d: path("M6.5 5.5a7.5 2 0 1 0 15 0a7.5 2 0 1 0-15 0Z");
}

</style>
