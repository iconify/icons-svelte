<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fbf28eboe"/><path class="lpmq4tukk"/><path class="xjf9nbcbc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mortgage-offer" {...props}></Icon>
<style>
:global(.fbf28eboe) {
  d: path("M2.5 12v7.5a2 2 0 0 0 2 2h15a2 2 0 0 0 2-2V12");
}

:global(.lpmq4tukk) {
  d: path("m2.5 12l9.5 5.5l9.5-5.5M5 11.5V4a1.5 1.5 0 0 1 1.5-1.5h11A1.5 1.5 0 0 1 19 4v7.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xjf9nbcbc) {
  d: path("m9 8l3-2.75L15 8v3H9Z");
}

</style>
