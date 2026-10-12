<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="c2225hbbf"/><circle class="o314m_b-p"/><path class="bf-rt3ghr"/><circle class="fqs7glzwp"/><path class="hkc5-wirk"/><circle class="hg2m77fua"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:first-steps-sharp" {...props}></Icon>
<style>
:global(.bf-rt3ghr) {
  d: path("M12 10.5h2V13c0 1.25-.5 1.75-.5 2.5V17h-2.75v-1.5c0-.75.5-1.25.5-2c0-.5-.75-1-.75-1.75V10.5z");
}

:global(.c2225hbbf) {
  d: path("M5.25 14.75h-2v2.5c0 1.25.5 1.75.5 2.5v1.5H6.5v-1.5c0-.75-.5-1.25-.5-2c0-.5.75-1 .75-1.75v-1.25z");
}

:global(.fqs7glzwp) {
  cx: 11.25px;
  cy: 8.25px;
  r: 1.25px;
}

:global(.hg2m77fua) {
  cx: 19.25px;
  cy: 4px;
  r: 1.25px;
}

:global(.hkc5-wirk) {
  d: path("M18.5 6.25h-2v2.5c0 1.25.5 1.75.5 2.5v1.5h2.75v-1.5c0-.75-.5-1.25-.5-2c0-.5.75-1 .75-1.75V6.25z");
}

:global(.o314m_b-p) {
  cx: 6px;
  cy: 12.5px;
  r: 1.25px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
