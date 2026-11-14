<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yh3o8-b_d"/><path class="m-52rc0bf"/><path class="jgie8bcwm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:directions-right" {...props}></Icon>
<style>
:global(.jgie8bcwm) {
  d: path("m13.5 8.5l2 2l-2 2");
}

:global(.m-52rc0bf) {
  d: path("M9.5 15.5v-3a2 2 0 0 1 2-2h4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yh3o8-b_d) {
  d: path("M12 2.25L21.75 12L12 21.75L2.25 12Z");
}

</style>
