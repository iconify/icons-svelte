<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bfq-__9qq"/><path class="hm_znik5w"/><path class="a05h5rbtq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:lighting-schedule" {...props}></Icon>
<style>
:global(.a05h5rbtq) {
  d: path("M17 15.25V17l1.75 1");
}

:global(.bfq-__9qq) {
  d: path("M5.5 21.5v-13a5 5 0 0 1 5-5h3v1.25");
}

:global(.hm_znik5w) {
  d: path("M10.75 7.5a2.75 2.75 0 0 1 5.5 0ZM3 21.5h5m4.5-4.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
