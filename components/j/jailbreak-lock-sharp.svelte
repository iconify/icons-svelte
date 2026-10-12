<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ct9w9mblk"/><path class="fknzpccmd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:jailbreak-lock-sharp" {...props}></Icon>
<style>
:global(.ct9w9mblk) {
  d: path("M8 10.25v-3.5a4 4 0 0 1 8 0v.5m-11.25 3h14.5v11H4.75z");
}

:global(.fknzpccmd) {
  d: path("m12.5 12.75l-1.75 2.75l2.5 1.5l-1.75 2.25");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
