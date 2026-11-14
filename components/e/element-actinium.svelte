<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fl1d8figg"/><path class="wyjc_m-sx"/><path class="jr8el6bas"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:element-actinium" {...props}></Icon>
<style>
:global(.fl1d8figg) {
  d: path("M2.5 12a9.5 3.5 0 1 0 19 0a9.5 3.5 0 1 0-19 0Z");
}

:global(.jr8el6bas) {
  d: path("M7.25 20.25a9.5 3.5 120 1 1 9.5-16.5a9.5 3.5 120 1 1-9.5 16.5M12 12h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wyjc_m-sx) {
  d: path("M16.75 20.25a9.5 3.5 60 1 1-9.5-16.5a9.5 3.5 60 1 1 9.5 16.5");
}

</style>
