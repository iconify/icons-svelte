<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f6vjuvbop"/><path class="spy07ybot"/><path class="e2nnbnb5l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:layers" {...props}></Icon>
<style>
:global(.e2nnbnb5l) {
  d: path("m3 16l9 5l9-5");
}

:global(.f6vjuvbop) {
  d: path("m12 3l9 5l-9 5l-9-5Z");
}

:global(.spy07ybot) {
  d: path("m3 12l9 5l9-5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
