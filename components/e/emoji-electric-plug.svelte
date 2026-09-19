<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zvs8p0bsw"/><path class="ql4ngu3kn"/><path class="wtw0c_nnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:emoji-electric-plug" {...props}></Icon>
<style>
:global(.ql4ngu3kn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.318 18.242v8c0 7 5.678 12.675 12.682 12.675s12.682-5.675 12.682-12.676v-8z");
}

:global(.wtw0c_nnm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.389 38.186l1.153 4.314h6.917l1.153-4.297");
}

:global(.zvs8p0bsw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.784 18.242V7.804A2.305 2.305 0 0 0 18.48 5.5h0a2.305 2.305 0 0 0-2.306 2.304h0v10.438m16.14 0V7.804A2.305 2.305 0 0 0 30.01 5.5h0a2.305 2.305 0 0 0-2.306 2.304h0v10.438");
}

</style>
