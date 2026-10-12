<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="dbgvcxwad"/><path class="tfs4-ubdm"/><path class="rfm7aobqj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pool-ball-sharp" {...props}></Icon>
<style>
:global(.dbgvcxwad) {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

:global(.rfm7aobqj) {
  d: path("M12 8.5a1.5 1.5 0 1 0 0 3a1.5 1.5 0 1 0 0-3Zm0 3a1.75 1.75 0 1 0 0 3.5a1.75 1.75 0 1 0 0-3.5Z");
}

:global(.tfs4-ubdm) {
  d: path("M12 5.75a6.25 6.25 0 1 0 0 12.5a6.25 6.25 0 1 0 0-12.5Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
