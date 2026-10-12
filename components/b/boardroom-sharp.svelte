<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ewrtu4bou"/><circle class="o-_1o3beq"/><circle class="ou244bblc"/><circle class="u38whcbki"/><circle class="dt7y3rbea"/><circle class="jcxm0gmcx"/><circle class="fbp8fgpqp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:boardroom-sharp" {...props}></Icon>
<style>
:global(.dt7y3rbea) {
  cx: 6.5px;
  cy: 19.5px;
  r: 1.25px;
}

:global(.ewrtu4bou) {
  d: path("M3.75 9.25h16.5v5.5H3.75z");
}

:global(.fbp8fgpqp) {
  cx: 17.5px;
  cy: 19.5px;
  r: 1.25px;
}

:global(.jcxm0gmcx) {
  cx: 12px;
  cy: 19.5px;
  r: 1.25px;
}

:global(.o-_1o3beq) {
  cx: 6.5px;
  cy: 4.5px;
  r: 1.25px;
}

:global(.ou244bblc) {
  cx: 12px;
  cy: 4.5px;
  r: 1.25px;
}

:global(.u38whcbki) {
  cx: 17.5px;
  cy: 4.5px;
  r: 1.25px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
