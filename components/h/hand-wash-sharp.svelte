<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xoqbjz4hr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:hand-wash-sharp" {...props}></Icon>
<style>
:global(.xoqbjz4hr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.75h9v3m0 2l1.5 2.029v.621a1.5 1.5 0 0 1-3 0v-.621zm-9 6.5h12.5l3.4-2.2a1.6 1.6 0 0 1 2 2.45l-4.3 4.65l-1.086 1.126l-1.564-.026H2.75V17.5Z");
}

</style>
