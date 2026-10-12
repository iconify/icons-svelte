<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="o3osnub4j"/><path class="pd3givbdd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:monitor-riser" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o3osnub4j) {
  width: 14.5px;
  height: 9.5px;
  x: 4.75px;
  y: 2.75px;
  rx: 1.5px;
}

:global(.pd3givbdd) {
  d: path("M12 12.25v2.5m-8.25 6.5v-6.5h16.5v6.5");
}

</style>
