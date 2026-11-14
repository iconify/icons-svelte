<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w-m366bmq"/><path class="quk2zcvog"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:account-student" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.quk2zcvog) {
  d: path("M7 12.5V17c2.5 2 7.5 2 10 0v-4.5");
}

:global(.w-m366bmq) {
  d: path("m12.728 5.405l5.912 3.284a1.5 1.5 0 0 1 0 2.622l-5.912 3.284a1.5 1.5 0 0 1-1.456 0L5.36 11.311a1.5 1.5 0 0 1 0-2.622l5.912-3.284a1.5 1.5 0 0 1 1.456 0");
}

</style>
