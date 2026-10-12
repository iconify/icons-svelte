<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="o2ebrftgp"/><circle class="wv5f_1brg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:dance-floor-sharp" {...props}></Icon>
<style>
:global(.o2ebrftgp) {
  d: path("M7.75 11.5H17l.3.69l3.65 8.37l.3.69H2.75l.3-.69l3.65-8.37l.3-.69zm4.25 0v9.75m-7.25-5h14.5");
}

:global(.wv5f_1brg) {
  cx: 12px;
  cy: 5.25px;
  r: 2.5px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
