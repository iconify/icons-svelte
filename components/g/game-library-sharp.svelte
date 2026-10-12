<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="zwfxj2-ok"/><path class="j8dptfx6y"/><path class="lb_gfvkvo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:game-library-sharp" {...props}></Icon>
<style>
:global(.j8dptfx6y) {
  d: path("M5.25 7.75v-2.5h13v13.5h-2.5");
}

:global(.lb_gfvkvo) {
  d: path("M2.75 7.75h13v13.5h-13zm3 0v13.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zwfxj2-ok) {
  d: path("M7.75 5.25v-2.5h13v13.5h-2.5");
}

</style>
