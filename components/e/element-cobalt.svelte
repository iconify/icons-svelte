<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j_psw1y4g"/><path class="qzec5sbpj"/><path class="k2kp2g75r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:element-cobalt" {...props}></Icon>
<style>
:global(.j_psw1y4g) {
  d: path("M3 3h18v18H3Z");
}

:global(.k2kp2g75r) {
  d: path("M7.25 9.25L12 12l4.75-2.75M12 12v5.5");
}

:global(.qzec5sbpj) {
  d: path("m12 6.5l4.75 2.75v5.5L12 17.5l-4.75-2.75v-5.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
