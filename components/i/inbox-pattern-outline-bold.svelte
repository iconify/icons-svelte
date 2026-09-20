<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="f-52c6b3g"/><path class="rr985ibot"/><path class="rqm7ypbhc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:inbox-pattern-outline-bold" {...props}></Icon>
<style>
:global(.f-52c6b3g) {
  d: path("M4 10v10h16V10");
}

:global(.rqm7ypbhc) {
  d: path("M9.5 5.5 12 8l2.5 -2.5");
}

:global(.rr985ibot) {
  d: path("M12 3v2.5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
