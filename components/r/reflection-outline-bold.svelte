<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="uverd3z0e"/><path class="k3x4ygb5y"/><path class="r_je2bdjk"/><path class="xyf3o9drf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:reflection-outline-bold" {...props}></Icon>
<style>
:global(.k3x4ygb5y) {
  d: path("M15.5 5.94a7 7 0 0 1 0 12.12");
}

:global(.r_je2bdjk) {
  d: path("M12 4v5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.uverd3z0e) {
  d: path("M8.5 18.06a7 7 0 0 1 0 -12.12");
}

:global(.xyf3o9drf) {
  d: path("M12 15v5");
}

</style>
