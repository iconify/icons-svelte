<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="wramcs5ip"/><path clip-rule="evenodd" class="f-q89ibyd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:calendar-alert-sharp" {...props}></Icon>
<style>
:global(.f-q89ibyd) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 20C18.552 20 19 20.448 19 21C19 21.552 18.552 22 18 22C17.448 22 17 21.552 17 21C17 20.448 17.448 20 18 20Z");
  stroke: none;
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.wramcs5ip) {
  d: path("M12 21H3V5H21V12M6 11H18M8 2V8M16 2V8M18 14V18");
}

</style>
