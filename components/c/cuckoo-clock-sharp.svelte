<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="h_dfmtkzx"/><path class="ou8ozwyfz"/><path class="lbi90ci2c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:cuckoo-clock-sharp" {...props}></Icon>
<style>
:global(.h_dfmtkzx) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.6 3.45l6.8 5.1l.6.45h-2v9H6V9H4l.6-.45l6.8-5.1L12 3z");
}

:global(.lbi90ci2c) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 20.75h.01m4.99-.5h.01");
}

:global(.ou8ozwyfz) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 12.25a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0ZM9.5 18v1.75m5-1.75v1.25");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
