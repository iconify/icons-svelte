<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="qml6lrdqn"/><path class="yreu97ylk"/><path class="n3bxrub0h"/><path class="ucws8vbwy"/><path class="qsm8r14by"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:no-dogs-sharp" {...props}></Icon>
<style>
:global(.n3bxrub0h) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.5 8a2.5 2 0 1 0 5 0a2.5 2 0 1 0-5 0Z");
}

:global(.qml6lrdqn) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 18a2.5 2 0 1 0 5 0a2.5 2 0 1 0-5 0Z");
}

:global(.qsm8r14by) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.75 3.75l16.5 16.5");
}

:global(.ucws8vbwy) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 4.75h.01m2.74-1.5h.01m2.74 1h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.yreu97ylk) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 14.75h.01m2.74-1.5h.01m2.74 1h.01");
}

</style>
