<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eh5cw8bnl"/><path class="zuqiwmbrd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:container-build" {...props}></Icon>
<style>
:global(.eh5cw8bnl) {
  d: path("M14.618 17.571L11 19.5l-7.5-4v-9l7.5-4l7.5 4v4.1");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zuqiwmbrd) {
  d: path("m3.5 6.5l7.5 4l7.5-4m-7.5 4v9m7.793-5.225l3.182 3.182l-1.768 1.768l-3.182-3.182ZM18.75 17.5L15 21.25");
}

</style>
