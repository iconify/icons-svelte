<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b4magua-x"/><path class="u7h7lpdvl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:camper-van" {...props}></Icon>
<style>
:global(.b4magua-x) {
  d: path("M2.5 15.5v-6a2 2 0 0 1 2-2h10.75c.75 0 1.25.25 1.75 1l3.75 3.5c.5.5.75 1 .75 1.75v1.75A1.5 1.5 0 0 1 20 17H4a1.5 1.5 0 0 1-1.5-1.5Zm2-8l1.25-4H13l1.25 4");
}

:global(.u7h7lpdvl) {
  d: path("M13 7.5V12h7M5 18a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
