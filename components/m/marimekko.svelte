<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="d1w8doz1s"/><rect class="hwdhpkbke"/><rect class="h_rol2rpq"/><rect class="mg93uqbhs"/><rect class="eprv77bqw"/><rect class="me2hbkbim"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:marimekko" {...props}></Icon>
<style>
:global(.d1w8doz1s) {
  width: 6px;
  height: 6.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 1px;
}

:global(.eprv77bqw) {
  width: 4.25px;
  height: 3.5px;
  x: 17px;
  y: 2.75px;
  rx: 1px;
}

:global(.h_rol2rpq) {
  width: 3.25px;
  height: 11px;
  x: 11.25px;
  y: 2.75px;
  rx: 1px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hwdhpkbke) {
  width: 6px;
  height: 9.5px;
  x: 2.75px;
  y: 11.75px;
  rx: 1px;
}

:global(.me2hbkbim) {
  width: 4.25px;
  height: 12.5px;
  x: 17px;
  y: 8.75px;
  rx: 1px;
}

:global(.mg93uqbhs) {
  width: 3.25px;
  height: 5px;
  x: 11.25px;
  y: 16.25px;
  rx: 1px;
}

</style>
