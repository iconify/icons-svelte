<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cck62wzax"/><path class="qvksdrblk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:city-hall-flag" {...props}></Icon>
<style>
:global(.cck62wzax) {
  d: path("M3 21v-8.5h5.5v-4h7v4H21V21M2.5 21h19M12 8.5v-6m0 0h4.5v3H12Z");
}

:global(.qvksdrblk) {
  d: path("M10 21v-3.5a2 2 0 0 1 4 0V21");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
