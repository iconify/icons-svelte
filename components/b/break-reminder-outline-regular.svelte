<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r57e8zbzz"/><path class="ng_tlibuk"/><path class="s0v-_1bji"/><path class="v9hia4w8h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:break-reminder-outline-regular" {...props}></Icon>
<style>
:global(.ng_tlibuk) {
  d: path("M15 9a3 3 0 0 1 0 6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.r57e8zbzz) {
  d: path("M4 9v9h11V9");
}

:global(.s0v-_1bji) {
  d: path("M7 3a3 3 0 0 1 0 6");
}

:global(.v9hia4w8h) {
  d: path("M12 3a3 3 0 0 1 0 6");
}

</style>
