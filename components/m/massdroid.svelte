<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s0hmlsbnn"/><path class="m1uhldb5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:massdroid" {...props}></Icon>
<style>
:global(.m1uhldb5f) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.01 23.916l2.728 4.178l7.002-15.692h7.544c6.447-.022 9.221 5.64 9.216 11.772c-.005 6.131-2.81 11.404-8.315 11.425h-6.771V21.028m3.578-3.868v13.822");
}

:global(.s0hmlsbnn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.5 35.599l9.938-23.197L20.2 20.54");
}

</style>
