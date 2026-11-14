<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gxaeo6b4y"/><path class="s4pazkb-h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:avalanche" {...props}></Icon>
<style>
:global(.gxaeo6b4y) {
  d: path("m2.5 20.5l7-16l4 8c2-1.25 4.75-.25 5 2c1.75 0 3 1.25 3 3s-1.25 3-3 3Z");
}

:global(.s4pazkb-h) {
  d: path("M12 17.5c.75-1.75 2.5-2.5 4.5-2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
