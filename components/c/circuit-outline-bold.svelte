<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vlo76ab2r"/><path class="qfgxpvbvs"/><path class="qrffjub9u"/><path class="xcm-54bzl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:circuit-outline-bold" {...props}></Icon>
<style>
:global(.qfgxpvbvs) {
  d: path("M6 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.qrffjub9u) {
  d: path("M12 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vlo76ab2r) {
  d: path("M2 17h5V7h6v10h6v-7");
}

:global(.xcm-54bzl) {
  d: path("M18 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
