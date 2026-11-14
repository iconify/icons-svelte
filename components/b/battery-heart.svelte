<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lm2lq82ov"/><path class="j53nzzbxi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:battery-heart" {...props}></Icon>
<style>
:global(.j53nzzbxi) {
  d: path("m12.75 9l-2 3.5h2.5l-2 3");
}

:global(.lm2lq82ov) {
  d: path("m12 20l-7-7a4.5 4.5 0 0 1 5.5-6.5v-2h3v2A4.5 4.5 0 0 1 19 13Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
