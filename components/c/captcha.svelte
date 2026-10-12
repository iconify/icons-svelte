<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="t0fnjfb_f"/><rect class="e3llb48zn"/><rect class="ysa-7fika"/><rect class="p8n9i911v"/><path class="ni6nfmb8z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:captcha" {...props}></Icon>
<style>
:global(.e3llb48zn) {
  width: 7.75px;
  height: 7.75px;
  x: 13.5px;
  y: 2.75px;
  rx: 1.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ni6nfmb8z) {
  d: path("m15.5 6.75l1.5 1.5l2.5-2.75m-14.75 12l1.5 1.5l2.5-2.75");
}

:global(.p8n9i911v) {
  width: 7.75px;
  height: 7.75px;
  x: 13.5px;
  y: 13.5px;
  rx: 1.5px;
}

:global(.t0fnjfb_f) {
  width: 7.75px;
  height: 7.75px;
  x: 2.75px;
  y: 2.75px;
  rx: 1.5px;
}

:global(.ysa-7fika) {
  width: 7.75px;
  height: 7.75px;
  x: 2.75px;
  y: 13.5px;
  rx: 1.5px;
}

</style>
