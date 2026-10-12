<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ipo2tnb5t"/><rect class="pgsg9_brh"/><path class="lfb-j4xcu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:roof-truss" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ipo2tnb5t) {
  d: path("M3.75 17L12 4.5L20.25 17");
}

:global(.lfb-j4xcu) {
  d: path("M12 4.5V17m-4.12-6.25L12 17l4.12-6.25");
}

:global(.pgsg9_brh) {
  width: 18.5px;
  height: 2.5px;
  x: 2.75px;
  y: 17px;
  rx: 0.75px;
}

</style>
