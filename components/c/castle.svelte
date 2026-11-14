<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o_z0nhg6w"/><path class="n5w2i237e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:castle" {...props}></Icon>
<style>
:global(.n5w2i237e) {
  d: path("M10 21v-5a2 2 0 0 1 4 0v5");
}

:global(.o_z0nhg6w) {
  d: path("M4 21V8h4v3h2V8h4v3h2V8h4v13Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
