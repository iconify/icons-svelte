<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="a88n32bnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:3dlut-mobile" {...props}></Icon>
<style>
:global(.a88n32bnt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.882 19.382v9.236H34.5m-13.137 0v-9.236h2.078a4.04 4.04 0 0 1 4.04 4.04v1.155a4.04 4.04 0 0 1-4.04 4.041zm-7.862-.779c.638.534 1.326.779 2.872.779h.36a2.308 2.308 0 1 0 0-4.617M13.5 20.154c.639-.533 1.328-.776 2.874-.772l.36.002a2.308 2.308 0 1 1 0 4.617m-1.775 0h1.774");
}

:global(.cpk0fnbgt) {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
