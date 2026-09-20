<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="pemn838wn"/><path class="l517yxbln"/><path class="e6ozu7b8f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:arcade-joystick-outline-bold" {...props}></Icon>
<style>
:global(.e6ozu7b8f) {
  d: path("M5 15v5h14v-5Z");
}

:global(.l517yxbln) {
  d: path("M12 9v6");
}

:global(.pemn838wn) {
  d: path("M9 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
