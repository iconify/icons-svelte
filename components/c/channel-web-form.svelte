<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ytl1s2brw"/><path class="o-f3ob8mp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:channel-web-form" {...props}></Icon>
<style>
:global(.o-f3ob8mp) {
  d: path("M14.5 10.5h3v3h-3Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ytl1s2brw) {
  d: path("M2.5 3.5h19v13h-19Zm9.5 13v4m-4 0h8m-9.5-13h11M6.5 12h5");
}

</style>
