<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="m6owtmb7h"/><circle class="v_-6mkj3f"/><circle class="xro3efbce"/><path class="ftct7ea9c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:harvest-basket-sharp" {...props}></Icon>
<style>
:global(.ftct7ea9c) {
  d: path("M8.75 10.5V9.25m6.5 1.25V9.25M3.75 14.5h17.5l-.32.95l-1.61 4.85l-.32.95H5l-.32-.95l-1.61-4.85l-.32-.95zm.1 3.35h16.3");
}

:global(.m6owtmb7h) {
  d: path("M3.75 14.5a8.25 8.25 0 0 1 16.5 0");
}

:global(.v_-6mkj3f) {
  cx: 8.75px;
  cy: 12.5px;
  r: 2px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xro3efbce) {
  cx: 15.25px;
  cy: 12.5px;
  r: 2px;
}

</style>
