<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="ht_zk-bpr"/><circle class="t88z8mbby"/><path class="pbatvs_xm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pocket-watch-sharp" {...props}></Icon>
<style>
:global(.ht_zk-bpr) {
  cx: 12px;
  cy: 14.75px;
  r: 6.5px;
}

:global(.pbatvs_xm) {
  d: path("M12 6.25v1.5m1.75-3.25h3.929l1.571 2.75M12 14.75V11.5m0 3.25l2.25 1.5");
}

:global(.t88z8mbby) {
  cx: 12px;
  cy: 4.5px;
  r: 1.75px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
