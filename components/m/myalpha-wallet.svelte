<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fzxjsqtbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:myalpha-wallet" {...props}></Icon>
<style>
:global(.fzxjsqtbl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m43.5 9.283l-9.566 29.434L24 9.283l-9.566 29.434L4.5 9.283");
}

</style>
