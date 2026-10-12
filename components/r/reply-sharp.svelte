<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="fmeosdblm"/><path class="kspidacpp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:reply-sharp" {...props}></Icon>
<style>
:global(.fmeosdblm) {
  d: path("m9.25 5.25l-5.5 5.5l5.5 5.5");
}

:global(.kspidacpp) {
  d: path("M3.75 10.75h9.5a7 7 0 0 1 7 7v1");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
