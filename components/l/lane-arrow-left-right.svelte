<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t6ed8ubto"/><path class="d7tjfwunm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:lane-arrow-left-right" {...props}></Icon>
<style>
:global(.d7tjfwunm) {
  d: path("M7.5 5L4 8.5L7.5 12m9-7L20 8.5L16.5 12");
}

:global(.t6ed8ubto) {
  d: path("M12 19.5v-7a4 4 0 0 0-4-4H4m8 4a4 4 0 0 1 4-4h4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
