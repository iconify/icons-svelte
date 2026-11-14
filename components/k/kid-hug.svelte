<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="asw92wb7h"/><path class="c6cn0gb7i"/><path class="zxtkb6xdc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:kid-hug" {...props}></Icon>
<style>
:global(.asw92wb7h) {
  d: path("M5 7a2.75 2.75 0 1 0 5.5 0A2.75 2.75 0 1 0 5 7Zm8.5 0A2.75 2.75 0 1 0 19 7a2.75 2.75 0 1 0-5.5 0Zm-11 13.5C2.5 16.5 5 14 8 14c1.5 0 2.75.75 3.75 1.75");
}

:global(.c6cn0gb7i) {
  d: path("M10 20.5c0-3.027 1.432-5.195 3.646-6.071");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zxtkb6xdc) {
  d: path("M10.25 19.5C8.75 18.25 7 18.25 5.5 19m13 2.5l-3-3a2 2 0 0 1 3-2.5a2 2 0 0 1 3 2.5Z");
}

</style>
