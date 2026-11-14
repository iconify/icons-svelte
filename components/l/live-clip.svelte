<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="utvjyfbuz"/><path class="br3ay8boo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:live-clip" {...props}></Icon>
<style>
:global(.br3ay8boo) {
  d: path("m9.75 6.5l5 2.75l-5 2.75ZM14 20.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm5 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-2.5-1L19.75 13m-.25 6.25L16.25 13");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.utvjyfbuz) {
  d: path("M14.4 15.5H2.5V3h19v7.8");
}

</style>
