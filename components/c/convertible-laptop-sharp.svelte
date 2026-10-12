<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iiamqvbux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:convertible-laptop-sharp" {...props}></Icon>
<style>
:global(.iiamqvbux) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 5h12v8H4zM3 17h18M19 5.54a4 4 0 0 1 0 6.92m2.24.2l-2.24-.2l.2-2.24");
}

</style>
