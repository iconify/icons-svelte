<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<ellipse transform="rotate(-34.12 12.97 29.193)" class="j9xk91bsa"/><ellipse transform="rotate(-55.88 35.03 29.485)" class="ofyxh3bwn"/><ellipse transform="rotate(-.263 23.846 13.496)" class="ufpzkkbvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:bouygues-telecom" {...props}></Icon>
<style>
:global(.j9xk91bsa) {
  cx: 12.97px;
  cy: 29.193px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.786px;
  ry: 12.452px;
}

:global(.ofyxh3bwn) {
  cx: 35.03px;
  cy: 29.485px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 12.452px;
  ry: 5.786px;
}

:global(.ufpzkkbvc) {
  cx: 23.854px;
  cy: 13.492px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 12.452px;
  ry: 5.786px;
}

</style>
