<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c54duacdo"/><path class="es4r-tbix"/><path class="iogxcvc1e"/><path class="hezebegwm"/><path class="ok7vombsg"/><path class="nrqy16b7j"/><path class="qnmmmsbha"/><path class="ldkstzszf"/><path class="l-utwubka"/><path class="jk6bn7bej"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:list-add-duotone-bold" {...props}></Icon>
<style>
:global(.c54duacdo) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 6h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.es4r-tbix) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 11h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hezebegwm) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18.5 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.iogxcvc1e) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 16h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jk6bn7bej) {
  d: path("M15.5 12h6");
}

:global(.l-utwubka) {
  d: path("M18.5 9v6");
}

:global(.ldkstzszf) {
  d: path("M3 16h11");
}

:global(.nrqy16b7j) {
  d: path("M3 6h11");
}

:global(.ok7vombsg) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15.5 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qnmmmsbha) {
  d: path("M3 11h11");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
