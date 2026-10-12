<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="okdz96b1z"/><path class="d_twlk4pa"/><rect class="tkkdodbov"/><path class="lekd1hbub"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bus-stop-shelter" {...props}></Icon>
<style>
:global(.d_twlk4pa) {
  d: path("M7 9.25v12");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lekd1hbub) {
  d: path("M12.75 12.75h8.5m-6.25 6v2m4-2v2");
}

:global(.okdz96b1z) {
  width: 6.5px;
  height: 6.5px;
  x: 3.75px;
  y: 2.75px;
  rx: 1.5px;
}

:global(.tkkdodbov) {
  width: 8.5px;
  height: 10px;
  x: 12.75px;
  y: 8.75px;
  rx: 2px;
}

</style>
