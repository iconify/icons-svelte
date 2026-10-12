<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o7z7dxbdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:binding-machine-sharp" {...props}></Icon>
<style>
:global(.o7z7dxbdl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 12.75v-8.5h8.5v8.5m3.5 0v-5.5l2.5-3m-17.5 8.5h18.5v8.5H2.75zm3.5 4h11.5");
}

</style>
