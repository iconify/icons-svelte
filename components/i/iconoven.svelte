<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vi6uyjsxu"/><rect class="d4lq2m26f"/><path class="lwttaibzg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:iconoven" {...props}></Icon>
<style>
:global(.d4lq2m26f) {
  width: 14.5px;
  height: 13px;
  x: 4.75px;
  y: 8.25px;
  rx: 3.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lwttaibzg) {
  d: path("M12 11.25q.42 3.08 3.5 3.5q-3.08.42-3.5 3.5q-.42-3.08-3.5-3.5q3.08-.42 3.5-3.5");
}

:global(.vi6uyjsxu) {
  d: path("M8.5 4.25v1m3.5-2v2m3.5-1v1");
}

</style>
