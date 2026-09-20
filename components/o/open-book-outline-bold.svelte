<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="gz0v-hb-h"/><path class="wioyn1brg"/><path class="l4mvwmb8t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:open-book-outline-bold" {...props}></Icon>
<style>
:global(.gz0v-hb-h) {
  d: path("M12 8Q9 5 3 5v12q6 0 9 3");
}

:global(.l4mvwmb8t) {
  d: path("m15 17 2 2 4 -4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wioyn1brg) {
  d: path("M12 8q3 -3 9 -3v12q-6 0 -9 3");
}

</style>
