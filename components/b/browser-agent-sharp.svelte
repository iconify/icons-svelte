<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="bbhyxubpd"/><path class="v_h_ylb4t"/><path class="jpx375bhx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:browser-agent-sharp" {...props}></Icon>
<style>
:global(.bbhyxubpd) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.75h18.5v16.5H2.75zm0 4.5h18.5");
}

:global(.jpx375bhx) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 10.5q.45 3.3 3.75 3.75q-3.3.45-3.75 3.75q-.45-3.3-3.75-3.75q3.3-.45 3.75-3.75Z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.v_h_ylb4t) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.75 6h.01");
}

</style>
