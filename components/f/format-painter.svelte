<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="babjej78c"/><path class="h997v6c4w"/><rect class="nbsf9snoc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:format-painter" {...props}></Icon>
<style>
:global(.babjej78c) {
  width: 12px;
  height: 5px;
  x: 2.75px;
  y: 2.75px;
  rx: 1.75px;
}

:global(.h997v6c4w) {
  d: path("M14.75 5.25h1a1.5 1.5 0 0 1 1.5 1.5V8.5a1.5 1.5 0 0 1-1.5 1.5h-7a1 1 0 0 0-1 1v2m4.5 8.25l4.5-9l4.5 9m-7.5-3h6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nbsf9snoc) {
  width: 3px;
  height: 8.25px;
  x: 6.25px;
  y: 13px;
  rx: 1px;
}

</style>
