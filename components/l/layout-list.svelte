<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="xow97lbdu"/><rect class="bae1z78bn"/><rect class="qm_s--bws"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:layout-list" {...props}></Icon>
<style>
:global(.bae1z78bn) {
  width: 18.5px;
  height: 4.16px;
  x: 2.75px;
  y: 9.92px;
  rx: 1.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qm_s--bws) {
  width: 18.5px;
  height: 4.17px;
  x: 2.75px;
  y: 17.08px;
  rx: 1.5px;
}

:global(.xow97lbdu) {
  width: 18.5px;
  height: 4.17px;
  x: 2.75px;
  y: 2.75px;
  rx: 1.5px;
}

</style>
