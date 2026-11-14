<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oi2sdyb_f"/><path class="quk2zcvog"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:account-student" {...props}></Icon>
<style>
:global(.oi2sdyb_f) {
  d: path("m12 5l9 5l-9 5l-9-5Z");
}

:global(.quk2zcvog) {
  d: path("M7 12.5V17c2.5 2 7.5 2 10 0v-4.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
