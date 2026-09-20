<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i25n86xeu"/><path class="gge15lbww"/><path class="z8ypwnuvu"/><path class="hvyszobfa"/><path class="lh0i37blz"/><path class="uw5kuce7r"/><path class="czysiurpc"/><path class="yg08zkbcc"/><path class="ah-zd_bma"/><path class="i699y-pkg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:jet-bridge-duotone-regular" {...props}></Icon>
<style>
:global(.ah-zd_bma) {
  d: path("M13 9v7");
}

:global(.czysiurpc) {
  d: path("M3 9h15v7H3");
}

:global(.gge15lbww) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 9h15v7H3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hvyszobfa) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 9v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.i25n86xeu) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.i699y-pkg) {
  d: path("M21 6v13");
}

:global(.lh0i37blz) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M21 6v13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.uw5kuce7r) {
  d: path("M3 3v18");
}

:global(.yg08zkbcc) {
  d: path("M8 9v7");
}

:global(.z8ypwnuvu) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 9v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
