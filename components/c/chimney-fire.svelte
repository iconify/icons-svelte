<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mf_rcdcjq"/><path class="iyczcob-r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:chimney-fire" {...props}></Icon>
<style>
:global(.iyczcob-r) {
  d: path("M17 2.5c1.75 1.75 2.25 2.75 2.25 3.5a2.25 2.25 0 0 1-4.5 0c0-.75.5-1.75 2.25-3.5Zm-7 19V17h4v4.5");
}

:global(.mf_rcdcjq) {
  d: path("m3 15.5l9-9l3.5 3.5V8.25h3V13l2.5 2.5m-16-2v8h14v-8");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
