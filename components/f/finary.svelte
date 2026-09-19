<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="efpfrgzud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:finary" {...props}></Icon>
<style>
:global(.efpfrgzud) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.889 21.947c6.412 0 11.611-5.199 11.611-11.612H17.111C10.7 10.335 5.5 15.534 5.5 21.947zM17.82 37.665c6.413 0 11.611-5.199 11.611-11.612h-12.32C10.7 26.053 5.5 31.252 5.5 37.665z");
}

</style>
