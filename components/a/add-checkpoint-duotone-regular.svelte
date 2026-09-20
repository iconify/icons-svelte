<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qlvopac9f"/><path class="qnvjj7b8l"/><path class="t7ftqibok"/><path class="tnh5d7byl"/><path class="crv4i00bu"/><path class="lulmb9b1a"/><path class="nb_catcjy"/><path class="jtt8g10_o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:add-checkpoint-duotone-regular" {...props}></Icon>
<style>
:global(.crv4i00bu) {
  d: path("M4 3v18");
}

:global(.jtt8g10_o) {
  d: path("M9 10h6");
}

:global(.lulmb9b1a) {
  d: path("M4 4h16v12H4");
}

:global(.nb_catcjy) {
  d: path("M12 7v6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qlvopac9f) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qnvjj7b8l) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 4h16v12H4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t7ftqibok) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 7v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tnh5d7byl) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 10h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
