<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y1z1czbul"/><path class="iymet_cml"/><path class="fwyf93qcw"/><path class="owfn5sxxm"/><path class="luzoskb2e"/><path class="taxmbub4q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:k-anonymity-duotone-thin" {...props}></Icon>
<style>
:global(.fwyf93qcw) {
  d: path("M8 8v6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iymet_cml) {
  d: path("M15.5 4H19a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V8l4 -4h3.5");
}

:global(.luzoskb2e) {
  d: path("M16 8v6");
}

:global(.owfn5sxxm) {
  d: path("M12 8v6");
}

:global(.taxmbub4q) {
  d: path("M6 17h12");
}

:global(.y1z1czbul) {
  fill: currentColor;
  d: path("M15.5 4H19a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V8l4 -4h3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
