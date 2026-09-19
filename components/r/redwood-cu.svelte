<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="j2n_v78el"/><path class="j55ye4b5o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:redwood-cu" {...props}></Icon>
<style>
:global(.j2n_v78el) {
  d: path("m27.62 17.316l3.616 12.641L27.033 43.5h-7.397");
}

:global(.j55ye4b5o) {
  d: path("M27.033 43.5h8.253l-4.05-13.543M12.714 43.5l11.525-39l3.397 13.047l-8 25.953z");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
