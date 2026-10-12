<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ok2jmgb0i"/><path class="owpy-pgkv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:ballet-flat-sharp" {...props}></Icon>
<style>
:global(.ok2jmgb0i) {
  d: path("M2.75 17.75V12l1 .25c1.75 1.5 5.75 2 9.25 1c4-.5 8.25 2 8.25 4.25v1.25H2.75z");
}

:global(.owpy-pgkv) {
  d: path("M7 13.75c1-3.5 4.5-3.75 5.75-.4");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
