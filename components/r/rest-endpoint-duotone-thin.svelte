<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fa8lp8ket"/><path class="ukyojkvtr"/><path class="mzjqjtrpb"/><path class="mp3xgab1v"/><path class="to02llleg"/><path class="jroakeb3a"/><path class="pty_wsbvs"/><path class="lnqk7fb0y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:rest-endpoint-duotone-thin" {...props}></Icon>
<style>
:global(.fa8lp8ket) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 4H3v16h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jroakeb3a) {
  d: path("M17 4h4v16h-4");
}

:global(.lnqk7fb0y) {
  d: path("M8 15h5");
}

:global(.mp3xgab1v) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 15h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mzjqjtrpb) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 9h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pty_wsbvs) {
  d: path("M8 9h8");
}

:global(.to02llleg) {
  d: path("M7 4H3v16h4");
}

:global(.ukyojkvtr) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 4h4v16h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
