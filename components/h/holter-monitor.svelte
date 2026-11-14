<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zoej7biec"/><path class="fvxj1lb1f"/><path class="qtepddfxl"/><path class="imju1h85n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:holter-monitor" {...props}></Icon>
<style>
:global(.fvxj1lb1f) {
  d: path("M13 15.5h5.5v4H13Z");
}

:global(.imju1h85n) {
  d: path("M14.5 15.5c-.5-3-4-4-5.75-5.5m7.75 5.5l-.75-5.75");
}

:global(.qtepddfxl) {
  fill: currentColor;
  d: path("M7 9a1.25 1.25 0 1 0 2.5 0A1.25 1.25 0 1 0 7 9Zm7.25-.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zoej7biec) {
  d: path("M9.5 2.5c0 1.75-1.25 2.5-3 3L5 6c-1.25.5-1.75 1.25-1.5 2.5l2.25 5c.25 1-.5 4-.5 8h13.5c0-4-.75-7-.5-8l2.25-5c.25-1.25-.25-2-1.5-2.5l-1.5-.5c-1.75-.5-3-1.25-3-3");
}

</style>
