<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="v-jogvb5z"/><path class="racsvxx3t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:event-spike-outline-bold" {...props}></Icon>
<style>
:global(.racsvxx3t) {
  d: path("M12 18h3l3 -3 3 3");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.v-jogvb5z) {
  d: path("m10 6 -5 5h4l-5 5");
}

</style>
