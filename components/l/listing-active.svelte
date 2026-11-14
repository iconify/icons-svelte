<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kstidlv3y"/><path class="oxf30sb5u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:listing-active" {...props}></Icon>
<style>
:global(.kstidlv3y) {
  d: path("M12.2 19.5H2.5v-15h19v10.3");
}

:global(.oxf30sb5u) {
  d: path("m5.5 10.5l4-4l3.99 3.99m-1.276 6.01H5.5v-6M16 9h3m-2.8 3H18m-3 2.5l6.5 3.5l-6.5 3.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
