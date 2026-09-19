<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="qwkxbobbi"/><circle class="pufyf9b7t"/><circle class="d4j_oj9fh"/><circle class="hk8myibbc"/><path class="t7rmjcc7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:purr" {...props}></Icon>
<style>
:global(.d4j_oj9fh) {
  cx: 38.371px;
  cy: 18.127px;
  r: 4.129px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.hk8myibbc) {
  cx: 29.628px;
  cy: 10.571px;
  r: 4.129px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.pufyf9b7t) {
  cx: 18.372px;
  cy: 10.571px;
  r: 4.129px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.qwkxbobbi) {
  cx: 9.629px;
  cy: 18.127px;
  r: 4.129px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.t7rmjcc7d) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 19.567c2.655 0 5.6 4.252 8.993 8.259c3.035 3.585 5.954 5.858 5.954 8.835c0 4.225-2.69 4.897-4.706 4.897S26.915 40.214 24 40.214s-8.225 1.344-10.241 1.344s-4.706-.672-4.706-4.897c0-2.977 2.919-5.25 5.954-8.835c3.393-4.007 6.338-8.259 8.993-8.259");
}

</style>
