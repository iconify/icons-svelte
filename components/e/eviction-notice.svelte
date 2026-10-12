<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r71z_8blh"/><path class="o4reiccib"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:eviction-notice" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o4reiccib) {
  d: path("M6.75 21v-3.5a2 2 0 0 1 4 0V21m5.75-5.5h4.75M19 13.25l2.25 2.25L19 17.75");
}

:global(.r71z_8blh) {
  d: path("m3.63 10.12l4.24-4.24q.88-.88 1.76 0l4.24 4.24q.88.88.88 2.13V20q0 1.25-1.25 1.25H4q-1.25 0-1.25-1.25v-7.75q0-1.25.88-2.13");
}

</style>
