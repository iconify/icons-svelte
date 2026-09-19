<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="sm4p5yayg"/><path class="c59n13bob"/><path class="ef851kmmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:planet-vpn" {...props}></Icon>
<style>
:global(.c59n13bob) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.545 22.928c.414 6.221-2.785 12.127-8.222 15.182s-12.146 2.715-17.247-.872m-5.136-5.94c-3.805-7.53-1.186-16.717 6.016-21.112s16.573-2.523 21.533 4.302");
}

:global(.ef851kmmv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.75 12.285c9.669-.616 2.667 5.88-4.098 11.373M27.7 27.469C21.508 31.39-.819 41.184 7.226 29.895");
}

:global(.sm4p5yayg) {
  cx: 30.549px;
  cy: 25.366px;
  r: 3.542px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
