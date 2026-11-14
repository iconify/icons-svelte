<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b9qwi0o7t"/><path class="zfgzjccvr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:component-create" {...props}></Icon>
<style>
:global(.b9qwi0o7t) {
  d: path("M12.183 19.834L11 20.5L3 16V7l8-4.5L19 7v5.221");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zfgzjccvr) {
  d: path("m3 7l8 4.5L19 7m-8 4.5v9m7-5.5v6m-3-3h6");
}

</style>
