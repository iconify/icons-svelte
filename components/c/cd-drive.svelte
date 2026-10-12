<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="apqag2bvo"/><path class="dpwr--7jr"/><path class="k-oiw3ayt"/><rect class="n6-4xacwx"/><circle class="biq2jjb5i"/><path class="tb6q2fbtf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:cd-drive" {...props}></Icon>
<style>
:global(.apqag2bvo) {
  width: 18.5px;
  height: 5px;
  x: 2.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

:global(.biq2jjb5i) {
  cx: 12px;
  cy: 15.75px;
  r: 3px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.dpwr--7jr) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 5.25h6");
}

:global(.k-oiw3ayt) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.25 5.25h.01");
}

:global(.n6-4xacwx) {
  width: 14.5px;
  height: 11px;
  x: 4.75px;
  y: 10.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

:global(.tb6q2fbtf) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 15.75h.01");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
