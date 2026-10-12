<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="dbgvcxwad"/><path class="stvj_3i7l"/><circle class="re_w6mbga"/><circle class="g06yjb6bk"/><path class="da8y-2bxi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pleading-face-sharp" {...props}></Icon>
<style>
:global(.da8y-2bxi) {
  d: path("m10.5 17l1.5-.9l1.5.9");
}

:global(.dbgvcxwad) {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

:global(.g06yjb6bk) {
  cx: 15px;
  cy: 11.25px;
  r: 2px;
}

:global(.re_w6mbga) {
  cx: 9px;
  cy: 11.25px;
  r: 2px;
}

:global(.stvj_3i7l) {
  d: path("M7.25 8.25L9.75 7m7 1.25L14.25 7");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
