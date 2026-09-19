<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="h01tyzbfu"><path class="ypphz-b-u"/><path class="ll3i0366u"/><path class="lrj0jmblu"/><path class="la4a_3bqz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:maif" {...props}></Icon>
<style>
:global(.h01tyzbfu) {
  fill: none;
  stroke: currentColor;
}

:global(.la4a_3bqz) {
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.787 30.618L26.945 24l2.157 6.638");
}

:global(.ll3i0366u) {
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.392 30.631V24l3.319 6.638l3.319-6.628v6.628m12.586-3.319h2.158m-2.158 3.319V24h3.319");
}

:global(.lrj0jmblu) {
  d: path("M28.38 28.418h-2.876");
}

:global(.ypphz-b-u) {
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.371 8.714L4.5 33.806l39 5.48zM31.859 24v6.638");
}

</style>
