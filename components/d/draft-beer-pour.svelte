<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="czfg-7bil"/><path class="lb7lqnp0y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:draft-beer-pour" {...props}></Icon>
<style>
:global(.czfg-7bil) {
  d: path("M4 3h7.5a2 2 0 0 1 2 2v3.75M8 9l1 12h9l1-12");
}

:global(.lb7lqnp0y) {
  d: path("M8.25 12q2.625-2.25 5.25 0t5.25 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
