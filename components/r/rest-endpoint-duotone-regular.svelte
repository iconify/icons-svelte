<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="f-7nb_bpw"/><path class="ilm81zbkk"/><path class="icdzo3brn"/><path class="skoarsb-l"/><path class="to02llleg"/><path class="jroakeb3a"/><path class="pty_wsbvs"/><path class="lnqk7fb0y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:rest-endpoint-duotone-regular" {...props}></Icon>
<style>
:global(.f-7nb_bpw) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 4H3v16h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.icdzo3brn) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 9h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ilm81zbkk) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 4h4v16h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jroakeb3a) {
  d: path("M17 4h4v16h-4");
}

:global(.lnqk7fb0y) {
  d: path("M8 15h5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pty_wsbvs) {
  d: path("M8 9h8");
}

:global(.skoarsb-l) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 15h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.to02llleg) {
  d: path("M7 4H3v16h4");
}

</style>
