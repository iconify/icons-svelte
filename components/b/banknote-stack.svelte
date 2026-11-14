<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n90aebc9n"/><path class="wu4jel-xu"/><path class="rumiejzbe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:banknote-stack" {...props}></Icon>
<style>
:global(.n90aebc9n) {
  d: path("M2.5 10h14v9h-14Z");
}

:global(.rumiejzbe) {
  d: path("M8 4.5h12.5A1.5 1.5 0 0 1 22 6v7.5M8 10v9m3-9v9");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wu4jel-xu) {
  d: path("M5.25 7.25h12.5a1.5 1.5 0 0 1 1.5 1.5v7.5");
}

</style>
