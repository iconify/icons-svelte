<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="snngwacrp"/><circle class="fbtpd61jd"/><path class="b9q52mbkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:mister-donut-alt-1" {...props}></Icon>
<style>
:global(.b9q52mbkz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.637 43.5V29.225L36.362 43.5V29.225z");
}

:global(.fbtpd61jd) {
  cx: 24px;
  cy: 16.863px;
  r: 4.121px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.snngwacrp) {
  cx: 24px;
  cy: 16.863px;
  r: 12.363px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
