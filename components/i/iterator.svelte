<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k_y2xpwaa"/><path class="u95zk4bjs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:iterator" {...props}></Icon>
<style>
:global(.k_y2xpwaa) {
  d: path("M16 5.072a8 8 0 1 1-8 0");
}

:global(.u95zk4bjs) {
  d: path("m5.25 4.25l3 .75l-.75 3M9 12h.01M12 12h.01M15 12h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
