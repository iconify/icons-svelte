<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="r7xk8o29f"/><path class="caznxbcdb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:arrow-up-outline-bold" {...props}></Icon>
<style>
:global(.caznxbcdb) {
  d: path("m7 9 5 -5 5 5");
}

:global(.r7xk8o29f) {
  d: path("M12 4v16");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
