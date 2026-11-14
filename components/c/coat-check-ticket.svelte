<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="anpy3ac0z"/><path class="oj552expk"/><path class="mobwjr4or"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:coat-check-ticket" {...props}></Icon>
<style>
:global(.anpy3ac0z) {
  d: path("M6.5 10.5L10 7h4l3.5 3.5v11h-11Z");
}

:global(.mobwjr4or) {
  d: path("M12 9.75c-6-8.25 6-8.25 0 0M9.5 15.5h5m-5 3h3");
}

:global(.oj552expk) {
  d: path("M10.5 11.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
