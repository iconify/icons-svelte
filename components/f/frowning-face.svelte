<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="rhvdvboaq"/><g class="fbp0m0b1e"><circle class="m5qjw3o7z"/><circle class="kyrv5hb3t"/><path class="ux5q7_bcf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:frowning-face" {...props}></Icon>
<style>
:global(.fbp0m0b1e) {
  fill: var(--svg-color--664e27, #664e27);
}

:global(.kyrv5hb3t) {
  cx: 43.5px;
  cy: 24.6px;
  r: 5px;
}

:global(.m5qjw3o7z) {
  cx: 20.5px;
  cy: 24.6px;
  r: 5px;
}

:global(.rhvdvboaq) {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffdd67, #ffdd67);
}

:global(.ux5q7_bcf) {
  d: path("M19.4 45.8c8.1-5.7 17.1-5.6 25.2 0c1 .7 1.8-.5 1.2-1.6c-2.5-4-7.4-7.7-13.8-7.7s-11.3 3.6-13.8 7.7c-.6 1.1.2 2.3 1.2 1.6");
}

</style>
