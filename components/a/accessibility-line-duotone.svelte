<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="doy9q4b5f"/><path class="srxr8c13n"/><path class="iloc7qlea"/><path class="qhkpc2vdh"/><path class="x6iuzrmkz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:accessibility-line-duotone" {...props}></Icon>
<style>
:global(.doy9q4b5f) {
  cx: 12px;
  cy: 12px;
  r: 10px;
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.iloc7qlea) {
  d: path("M18 10C18 10 14.4627 11.5 12 11.5C9.53727 11.5 6 10 6 10");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qhkpc2vdh) {
  d: path("M12 12V13.4522C12 14.0275 12.1654 14.5906 12.4765 15.0745L15 19");
}

:global(.srxr8c13n) {
  d: path("M14 7C14 8.10457 13.1046 9 12 9C10.8954 9 10 8.10457 10 7C10 5.89543 10.8954 5 12 5C13.1046 5 14 5.89543 14 7Z");
}

:global(.x6iuzrmkz) {
  d: path("M12 12V13.4522C12 14.0275 11.8346 14.5906 11.5235 15.0745L9 19");
}

</style>
