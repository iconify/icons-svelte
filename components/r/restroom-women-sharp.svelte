<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="t8yaf7baj"/><path class="b1bb71pqs"/><circle class="m7gj_g5yk"/><path class="wdaup3zyc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:restroom-women-sharp" {...props}></Icon>
<style>
:global(.b1bb71pqs) {
  d: path("M4.25 9.25h4.5v12h-4.5z");
}

:global(.m7gj_g5yk) {
  cx: 17.9px;
  cy: 4.5px;
  r: 1.75px;
}

:global(.t8yaf7baj) {
  cx: 6.5px;
  cy: 4.5px;
  r: 1.75px;
}

:global(.wdaup3zyc) {
  d: path("M17.5 9.25h1.75l.24.97l1.27 5.06l.24.97h-6.25l.24-.97l1.27-5.06l.24-.97zm.4 7v5m-6.15-18.5v18.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
