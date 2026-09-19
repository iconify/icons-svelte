<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bcyibqbnn"/><path class="lv1c3jb8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:musixmatch" {...props}></Icon>
<style>
:global(.bcyibqbnn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.5 31.2l31-24.1c2.4-1.9 6-.2 6 2.9v28c0 3.1-3.5 4.8-6 2.9l-31-24.1");
}

:global(.lv1c3jb8e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m42.5 31.2l-31-24.1c-2.4-1.9-6-.2-6 2.9v28c0 3.1 3.5 4.8 6 2.9l31-24.1");
}

</style>
