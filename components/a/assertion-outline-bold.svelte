<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="bq4e1jb8b"/><path class="o8od38cnm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:assertion-outline-bold" {...props}></Icon>
<style>
:global(.bq4e1jb8b) {
  d: path("m7 10 3 3 7 -7");
}

:global(.o8od38cnm) {
  d: path("M4 18h16");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
