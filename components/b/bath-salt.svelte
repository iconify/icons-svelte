<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="kt8s0oi2f"/><rect class="iinrrlyhq"/><path class="w-amiuzjk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bath-salt" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iinrrlyhq) {
  width: 9px;
  height: 12.5px;
  x: 2.75px;
  y: 8.75px;
  rx: 2.5px;
}

:global(.kt8s0oi2f) {
  width: 6px;
  height: 3px;
  x: 4.25px;
  y: 2.75px;
  rx: 1px;
}

:global(.w-amiuzjk) {
  d: path("m16.52 19.88l-.84.84q-.28.28-.56 0l-.84-.84q-.28-.28 0-.56l.84-.84q.28-.28.56 0l.84.84q.28.28 0 .56m4.45 0l-.84.84q-.28.28-.56 0l-.84-.84q-.28-.28 0-.56l.84-.84q.28-.28.56 0l.84.84q.28.28 0 .56m-2.25-5l-.84.84q-.28.28-.56 0l-.84-.84q-.28-.28 0-.56l.84-.84q.28-.28.56 0l.84.84q.28.28 0 .56");
}

</style>
