<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cuo_lzbeg"/><rect class="tfzzp3bib"/><rect class="gxvw2gb7g"/><path class="hd0mkacpw"/><rect class="zami1uhub"/><rect class="dx5yimbhm"/><path class="fbe1xtbnv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:dumbbell-rack" {...props}></Icon>
<style>
:global(.cuo_lzbeg) {
  d: path("M3.75 2.75v18.5m16.5-18.5v18.5m-16.5-10.5h16.5m-16.5 10h16.5");
}

:global(.dx5yimbhm) {
  width: 2.5px;
  height: 5px;
  x: 14.75px;
  y: 13.25px;
  rx: 1px;
}

:global(.fbe1xtbnv) {
  d: path("M9.25 15.75h5.5");
}

:global(.gxvw2gb7g) {
  width: 2.5px;
  height: 5px;
  x: 14.75px;
  y: 3.25px;
  rx: 1px;
}

:global(.hd0mkacpw) {
  d: path("M9.25 5.75h5.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.tfzzp3bib) {
  width: 2.5px;
  height: 5px;
  x: 6.75px;
  y: 3.25px;
  rx: 1px;
}

:global(.zami1uhub) {
  width: 2.5px;
  height: 5px;
  x: 6.75px;
  y: 13.25px;
  rx: 1px;
}

</style>
