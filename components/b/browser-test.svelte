<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n578xhy5u"/><path class="hzxar2bus"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:browser-test" {...props}></Icon>
<style>
:global(.hzxar2bus) {
  d: path("M7.5 12.75h9v5.5h-9Zm2.75 2.75h.01m3.49 0h.01");
}

:global(.n578xhy5u) {
  d: path("M2.5 3h19v18h-19Zm0 5h19m-16-2.5h.01M8 5.5h.01M12 10.75v2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
