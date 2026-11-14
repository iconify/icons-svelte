<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t1lgv37hw"/><path class="t4o0k0u_u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mortgage-help-to-buy" {...props}></Icon>
<style>
:global(.t1lgv37hw) {
  d: path("M11.36 20.5H4v-10l8-7l7.654 6.697");
}

:global(.t4o0k0u_u) {
  d: path("M16 7V4h2v4.75M14 21.5l3.75-7.75m-.5 7.75L21 13.75m-6 5.75h3.25m-2.25-2h3.25m-2.5-2H20");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
