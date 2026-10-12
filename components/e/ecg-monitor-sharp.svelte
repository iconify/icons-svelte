<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="oxra4ebya"/><path class="nu-m9ja-i"/><path class="k3rn56b2a"/><path class="ay-4n51cv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:ecg-monitor-sharp" {...props}></Icon>
<style>
:global(.ay-4n51cv) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 16.25v5m-4 0h8");
}

:global(.k3rn56b2a) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.5 7.5h.01m-.01 4.75h.01");
}

:global(.nu-m9ja-i) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 8h2l1-1.75l1.25 3.5l1-1.75h2m-7.25 5l1.2-2.4l.8 2.4l.8 2.4l1.2-2.4l1-2l1 2m4.5-9.25v12.5");
}

:global(.oxra4ebya) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.75h18.5v12.5H2.75z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
