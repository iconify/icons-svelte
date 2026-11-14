<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pq9rx6b_j"/><path class="gex6ffbtl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:hybrid-schedule" {...props}></Icon>
<style>
:global(.gex6ffbtl) {
  d: path("m14 17.75l3.75-3.5l3.75 3.5v3.75H14Zm3.75 3.75v-2.25");
}

:global(.pq9rx6b_j) {
  d: path("M11.2 21H3.5V4.5h17V13M8 2.5v4m8-4v4m-12.5 3h17");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
