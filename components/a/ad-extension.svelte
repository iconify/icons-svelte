<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o3koy_bjb"/><path class="q231xzpdr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ad-extension" {...props}></Icon>
<style>
:global(.o3koy_bjb) {
  d: path("M12.2 18H2.5V4h19v11.2");
}

:global(.q231xzpdr) {
  d: path("M6 7.5h5v7H6Zm8 2h4M14 13h1.2m2.8 2v6m-3-3h6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
