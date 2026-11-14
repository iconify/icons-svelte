<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="atfm7mb2i"/><path class="y9oe4n3ki"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:dual-fisheye" {...props}></Icon>
<style>
:global(.atfm7mb2i) {
  d: path("M2.25 12a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Zm10.5 0a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y9oe4n3ki) {
  d: path("M4.25 12a2.5 2.5 0 0 1 2.5-2.5m8 2.5a2.5 2.5 0 0 1 2.5-2.5");
}

</style>
