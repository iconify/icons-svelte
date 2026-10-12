<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="m0puv5hyc"/><rect class="lb66kio2d"/><path class="dvwm1ebao"/><path class="sosl8ibaa"/><path class="z6roz0jre"/><path class="pgcoinqya"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:claw-machine" {...props}></Icon>
<style>
:global(.dvwm1ebao) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 5.75v2.5m-2.5 3.5l-.5-1.5l1-2h4l1 2l-.5 1.5");
}

:global(.lb66kio2d) {
  width: 11px;
  height: 9.5px;
  x: 6.5px;
  y: 5.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

:global(.m0puv5hyc) {
  width: 17px;
  height: 18.5px;
  x: 3.5px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

:global(.pgcoinqya) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.75 18.25h.01");
}

:global(.sosl8ibaa) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 13.5h.01");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.z6roz0jre) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 18.25h3");
}

</style>
