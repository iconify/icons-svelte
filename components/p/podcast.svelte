<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wazu07lxd"/><path class="ktkubeu1u"/><path class="j0o8opbll"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:podcast" {...props}></Icon>
<style>
:global(.j0o8opbll) {
  d: path("M5.636 17.364a9 9 0 1 1 12.728 0");
}

:global(.ktkubeu1u) {
  d: path("M8.465 15.213a5.5 5.5 0 1 1 7.07 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wazu07lxd) {
  d: path("M9.75 11a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM12 15.5v6");
}

</style>
