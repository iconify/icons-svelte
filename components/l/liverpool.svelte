<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tj7ae3ygd"/><path class="uikp76bai"/><path class="l6pt3-ics"/><path class="j2kbg3beo"/><path class="bdq56-g1r"/><path class="e4ax_gbdc"/><path class="dnz2yibma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:liverpool" {...props}></Icon>
<style>
:global(.bdq56-g1r) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.573 7.182v21.527c0 1.346 1.345 2.691 2.69 2.691h10.091");
}

:global(.dnz2yibma) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 7.182v30.945c0 1.346 1.346 2.691 2.69 2.691h18.164");
}

:global(.e4ax_gbdc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.536 7.182v26.236c0 1.346 1.346 2.691 2.691 2.691h14.128");
}

:global(.j2kbg3beo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 40.818V9.873c0-1.346-1.345-2.691-2.69-2.691H21.645m-4.035 0V24c0 1.346 1.345 2.69 2.69 2.69h6.055");
}

:global(.l6pt3-ics) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.464 40.818V14.582c0-1.346-1.346-2.691-2.691-2.691H21.645");
}

:global(.tj7ae3ygd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.39 40.818V24c0-1.346-1.345-2.69-2.69-2.69h-6.054");
}

:global(.uikp76bai) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.427 40.818V19.291c0-1.346-1.345-2.691-2.69-2.691H21.645");
}

</style>
