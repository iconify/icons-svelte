<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mheqxacnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:34hd" {...props}></Icon>
<style>
:global(.mheqxacnc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.5 12.549l9.514 25.119L24 10.332l9.986 27.336l9.514-25.12L24 32.399z");
}

</style>
