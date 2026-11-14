<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m-9559bdj"/><path class="ufxm70bry"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:internet-cafe" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m-9559bdj) {
  d: path("m4.138 9.475l6.75-5.559a1.75 1.75 0 0 1 2.224 0l6.75 5.559a1.75 1.75 0 0 1 .638 1.351v8.424A1.75 1.75 0 0 1 18.75 21H5.25a1.75 1.75 0 0 1-1.75-1.75v-8.424a1.75 1.75 0 0 1 .638-1.351");
}

:global(.ufxm70bry) {
  d: path("M8.75 11h6.5A1.75 1.75 0 0 1 17 12.75v2a1.75 1.75 0 0 1-1.75 1.75h-6.5A1.75 1.75 0 0 1 7 14.75v-2A1.75 1.75 0 0 1 8.75 11M12 16.5v1.75m-2.5 0h5");
}

</style>
