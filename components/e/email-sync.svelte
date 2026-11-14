<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="os4esubmw"/><path class="s3a5wbbwq"/><path class="b1csntfxh"/><path class="opjjxbd2k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:email-sync" {...props}></Icon>
<style>
:global(.b1csntfxh) {
  d: path("M20.75 14.5v2h-2M21 18a3 3 0 0 1-5.5 1.5");
}

:global(.opjjxbd2k) {
  d: path("M15.25 21.5v-2h2");
}

:global(.os4esubmw) {
  d: path("M12 18.5H2.5v-13h19v6.2");
}

:global(.s3a5wbbwq) {
  d: path("m2.5 7l9.5 6l9.5-6M15 18a3 3 0 0 1 5.5-1.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
