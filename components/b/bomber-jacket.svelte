<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mjumdiw1y"/><path class="y08mj6bui"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bomber-jacket" {...props}></Icon>
<style>
:global(.mjumdiw1y) {
  d: path("M9 3L5 4.5C3.75 5 3 6 3 7.5V19h3.5l1-8v10h9V11l1 8H21V7.5c0-1.5-.75-2.5-2-3L15 3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y08mj6bui) {
  d: path("M9 3q3 3.5 6 0m-3 1.75V21m-4.5-2.5h9M3 17h3.75m10.5 0H21");
}

</style>
